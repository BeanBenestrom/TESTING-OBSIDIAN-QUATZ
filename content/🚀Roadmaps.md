```dataviewjs  

let IMG_ID = 0;
const SHOW_OLD = false;

const SORTERS = {
	"ascending"  : 
		(a, b) => ENTRY(a).name.toLowerCase() < ENTRY(b).name.toLowerCase() ? 1 : -1,
	"descending" : 
		(a, b) => ENTRY(a).name.toLowerCase() > ENTRY(b).name.toLowerCase() ? 1 : -1,
	"order"      : 
		(a, b) => ENTRY(a).order < ENTRY(b).order ? 1 : -1,
}

function ENTRY(project) {
	return project.head_of_group ? project.head_of_group : project;
}

function SORTING_KEY_MAPPER(name) {
	name = name == "asc"  ? "ascending"  : name;
	name = name == "desc" ? "descending" : name;
	return SORTERS[name];
} 

// console.log(SORTING_KEY_MAPPER("asc")("ABC", "BCA"));

const drawFunction = async (pointerRows) => {
	// DEV
	const devColor = false;
	let bc = "background-color"
	if (!devColor) { bc = ""; }
	
	// Base
	let pointerList = document.getElementById("pointer-list");
	if (pointerList) { pointerList.remove(); }
	pointerList = document.createElement("div");
	pointerList.id = "pointer-list"
	pointerList.style.cssText = 
	`display: flex; flex-direction: column; align-items: end; ${bc}: gold;`
	
	
	async function pointer_component(entry, color) {
		let pointer = document.createElement("div");
		pointer.style.cssText = 
		`width: 600px; display: flex; flex-direction: row; align-items: center;padding: 3px; margin-left: auto; background-color: ${color}; margin-bottom: 5px; margin-top: 5px; font-size: 1em; text-shadow: -1px -1px 1px #000, 1px -1px 1px #000, -1px 1px 1px #000, 1px 1px 1px #000; border-radius: 3px 0 0 3px`;
		// pointer.textContent = name;
		
		// let containerImg = document.createElement("div");
		dv.paragraph(`<span id="pointer_img_id_${IMG_ID}">${entry.image}</span>`)
		// let containerImg = document.getElementById(`pointer_img_id_${IMG_ID}`)
		// containerImg.innerHTML = entry.image;
		let containerImg = (await UTILITY_MODULE.waitForElements(`#pointer_img_id_${IMG_ID}`))[0];
		IMG_ID++;
		
		
		let container = document.createElement("div");
		container.style.cssText = 
		`flex-grow: 1; ${bc}: purple;`;
		
		let name_container = document.createElement("div");
		name_container.style.cssText = 
		`display: inline-block; width: 40%; ${bc}: white; padding: 5px; vertical-align: middle;`
		let name_div = document.createElement("span");
		name_div.style.cssText = `${bc}: rgb(200, 200, 200);`;
		let time_container = document.createElement("div");
		time_container.style.cssText = 
		`display: inline-block; width: 60%; ${bc}: green; padding: 5px; vertical-align: middle;`
		let time_div = document.createElement("span");
		time_div.style.cssText = `${bc}: lime;`;
		name_container.appendChild(name_div);
		time_container.appendChild(time_div);
		
		name_div.innerHTML = entry.entry1;
		time_div.innerHTML = entry.entry2;
		
		pointer.appendChild(containerImg);
		container.appendChild(name_container);
		container.appendChild(time_container);
		
		pointer.appendChild(container);
		
		return pointer;
	}
	
	async function group_component(entry, container_id, color) {
		let group = document.createElement("div");
	  group.style.cssText = 
	  `position:relative; background-color: rgb(${entry.groupColor}, 0.2); padding: 10px 0 10px 10px; margin-bottom: 10px; box-shadow: 0px 0px 2px 2px rgba(0, 0, 0, 0.5); border-radius: 2px 2px 2px 2px; overflow: hidden; border: 2px rgb(${entry.groupColor}) solid; border-width: 0px 0px 0px 0px;`;
	  let bar = document.createElement("div");
	  bar.style.cssText = 
	  `position: absolute; width: 5px; height: 100%; background-color: rgb(${entry.groupColor}); left: 0px; top: 0px;`;
	  group.appendChild(bar);
	  
	  let group_container = document.createElement("div");
	  group_container.style.cssText = 
	  `margin-bottom: 15px; width: fit-content; margin-left: auto;`
	  
	  let pointer_container = document.createElement("div");
	  pointer_container.id = container_id;
	  pointer_container.style.cssText = 
	  `width: auto; ${bc}: red;`
		
		let group_pointer = await pointer_component(entry, `rgb(${entry.groupColor}, 1)`);
	  group_container.appendChild(group_pointer);
	  group.appendChild(group_container);
	  group.appendChild(pointer_container);
	  return [group, pointer_container];
	}
	
	// Project base
	let parsed_projects = [];
	
	function parse_projects(projects) {
		let groups = {};
		projects.forEach( project => {
			if (!project.groups || !project.groups.length) {
		    	if (!groups.none) { groups.none = []; }
		    	groups.none.push(project);
		    } else {
			    for (let i=0; i<project.groups.length; i++) {
			    	if (!groups[project.groups[i]]) { groups[project.groups[i]] = []; }
			    	groups[project.groups[i]].push(project);
			    }
		    }
		});
		  
		const iterativeBuild = (target, list) => {	
			list.forEach( k => {
		    	if (groups[k.name]) {	// If project is a group
			        let group = { head_of_group: k, list: [] }; 	
			        iterativeBuild(group.list, groups[k.name]);
			        target.push(group);
			    } else {
					target.push(k);
			    }
		    });	
		}; 
		const iterativeSort = (data, sortType="") => {	
			data.forEach( k => { 
				if (k.head_of_group) 
					iterativeSort(k.list, k.head_of_group.sortType);
			});
			if (!sortType) return;
			data.sort(SORTING_KEY_MAPPER(sortType));
		}; 
		iterativeBuild(parsed_projects, groups.none);
		iterativeSort(parsed_projects);
	}
	
	
	async function build(parent, data) {
		for (let i=0; i<data.length; i++) {
			k = data[i];
			if (k.head_of_group) {
		    	let [group, list] = await group_component(k.head_of_group, "id:group-", "red");
				parent.appendChild(group);
			    await build(list, k.list);
		    } else {
		    	parent.appendChild(await pointer_component(k, "rgb(50, 50, 50, 0.0)"));
		    }
		}
	}
	
	parse_projects(pointerRows);
	await build(pointerList, parsed_projects);
		
	dv.paragraph(pointerList);
}


// Settings

let logoPath = this.app.vault.adapter.basePath + "/Attachments/icons";
let imageSize = "30px";
let imageOffset = "3px";  // To correct any mistakes from the centering image with text
let marginRight = "10px";

let headerSize = "1.8rem";
let infoNameOffset = "-8px";
let entryOffset = "-7px";  // 

let dayLimit = 30 * 1 / 10; // days
let dynamic = true;   // limit is depending on pointer amount; dayLimit per pointer

// MODULES

if (!module.exports.color) dv.executeJs(await dv.io.load("Scripts/color.js"));
if (!module.exports.date)  dv.executeJs(await dv.io.load("Scripts/date.js"));
if (!module.exports.utility) dv.executeJs(await dv.io.load("Scripts/utility.js"));

const COLOR_MODULE = module.exports.color;
const DATE_MODULE = module.exports.date;
const UTILITY_MODULE = module.exports.utility;
const COLOR_MODULE_GtoRcg = COLOR_MODULE.greenToRedCircleGradient;

// FUNCTIONS

const pathToImage = (name) => `<span 
	src="${logoPath}/${name}.png" alt="${name}"
	class="internal-embed media-embed image-embed is-loaded" 
	style="
		display: flex;
		justify-content: center;  
		align-items: center;
		position: relative; width: auto; height: 30px; background-color: rgb(0, 0, 0, 0.5); margin-right: 5px;  vertical-align: middle; border-radius: 3px;
	">
	<img 
		height="${imageSize}"
		alt="${name}"
		src="${logoPath}/${name}.png"
	>	
</span>`;

function image_html(imageName, options="")
{
	let image = pathToImage(imageName);
	return image;
}

const textToLink = (path, name) => `<a aria-label-position="top" aria-label="${path}" data-href="${path}" href="${path}" class="internal-link" target="_blank" rel="noopener">${name}</a>`

// GET POINTERS

const get_old = t => t.frontmatter.tags.find( tag => tag == "old" );
const get_not_old = t => !t.frontmatter.tags.find( tag => tag == "old" );

const old_func = SHOW_OLD ? get_old : get_not_old;

let pages = dv.pages("#roadmap")
				.file.where(t => t.folder != "Templates")
				.where(t => t.folder != "__meta__/Notes")
				.where(t => old_func(t))
				.sort(f => f.frontmatter.ctime, "asc")

// RENDER POINTERS

if (pages.length)
{
	let pointerRows = [];
	dayLimit *= pages.length;
	
	for (let i = 0; i < pages.length; i++)
	{
		// Get any needed entry information
		
		let entry = {};
		
		entry.path = pages[i].path;
		entry.name = pages[i].name.replace(" POINTER", "");
		entry.ctime = pages[i].frontmatter.ctime;
		
		entry.started = pages[i].frontmatter.started;
		entry.completed = pages[i].frontmatter.completed;
		entry.lastWorkedOn = pages[i].frontmatter.lastWorkedOn;
		entry.deadline = pages[i].frontmatter.deadline;
		entry.groupColor = pages[i].frontmatter.groupColor;
		entry.groups = (pages[i].frontmatter.groups || []);
		entry.sortType = (pages[i].frontmatter.sortType || "").toLowerCase();
		entry.order    = (pages[i].frontmatter.order || -1);
		// console.log(entry.name, entry.groups);
		
		let CSoptions = "";
		if (entry.groupColor) 
			CSoptions = `padding: 1px; border: 1px solid ${entry.groupColor};`;
		
		entry.image = image_html(pages[i].frontmatter.img, CSoptions);
		
		// Actual row entries
		
		entry.entry1 = `${textToLink(entry.path, entry.name)}`;
		entry.entry2 = "";
		if (entry.lastWorkedOn)
		{
			entry.entry2 = "undefined";
			let daysSinceProgress = DATE_MODULE.daysSince(entry.lastWorkedOn);
			if (daysSinceProgress)
			{
				let howLongAgo = DATE_MODULE.sinceDaysMessage(daysSinceProgress);
				let {r:r, g:g} = COLOR_MODULE_GtoRcg(daysSinceProgress / dayLimit, 400);
				entry.entry2 = `<font style="color: rgb(${r}, ${g}, 0);">${howLongAgo}</font>`;
			} else if (daysSinceProgress === 0) {
				entry.entry2 = `<font style="color: rgb(0, 255, 0)">Today</font>`;
			}
		}
		entry.entry3 = `<font style="color: red">${(entry.deadline || "")}</font>`;
		
		// Add to array
		pointerRows.push(entry);
	}
	
	// DRAW
	
	drawFunction(pointerRows);
}
```