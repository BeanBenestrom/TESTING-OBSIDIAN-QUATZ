<div style="background-color: rgb(0,0,0,0.5); padding: 2px; border-radius: 2px; color: grey">
<font style="font-style: italic; color: rgb(100,100,100,0.8)">Related topic:</font> <br>
🎥video, 👨‍💻CS
</div>

```dataviewjs
let tp = app.plugins.plugins["templater-obsidian"].templater.current_functions_object
if (!tp) { dv.paragraph("<font style='color: red'>tp not loaded!</font>"); return; }


const main = async _ => {

let text = "";

let container = document.createElement("div");
container.style.cssText = "position: relative;";
let outline = document.createElement("div");
let formatDiv = document.createElement("div");
const boverCSS = `position: absolute; width: calc(100% + 10px); height: calc(100% + 10px); top: -5px; right: -5px; border: 1px grey solid; background-color: rgb(0,0,0,0.1); border-radius: 2px`;
outline.style.cssText = "";
container.appendChild(outline);
container.appendChild(formatDiv);


async function create_file(fileName="", text="", templatePath="") {
	let templateText = "";
	if (templatePath) 
		templateText = await dv.io.load(tp.file.find_tfile(templatePath).path);
	await tp.file.create_new(templateText + text, fileName, false, app.vault.getAbstractFileByPath("🗄️scratchpad"))
}

async function createTextArea(style=null, defaultText=null, id=null)
{
	let area = document.createElement("textarea");
	if (id)    area.setAttribute("id", id);
	if (style) area.style.cssText = style;
	if (text)  area.placeholder=(defaultText || "");
	area.name = "poop"; area.rows = 5; area.cols = 33;
	
	area.addEventListener('input', function() {
		text = area.value;
		area.value = text;
		// event handling code for sane browsers
		if (area.value != "") outline.style.cssText = boverCSS;
		else                  outline.style.cssText = "";
		Array.from(formatDiv.children).forEach( child => child.remove() );
		tp.obsidian.MarkdownRenderer.render(app, area.value, formatDiv, "", formatDiv);
	}, false);
	return area;
}

let textArea = await createTextArea();

async function createButton(func=null, style=null, text=null, id=null)
{
	let button = document.createElement("BUTTON");
	if (id)    button.setAttribute("id", id);
	if (style) button.style.cssText = style;
	if (text)  button.append(text);
	
	if (func) 
	{
		button.addEventListener('click', async function (e) {
			e.stopPropagation();
			await func();
		});
	}
	
	return button;
}

let style = "background-color: red";
let button = await createButton(async () => { 
	await create_file(
		(new Date()).toISOString().split('T')[0], 
		textArea.value, 
		"scratchpad"
	);
}, style, "Add File", "scrachpad-file-creator-button")

dv.paragraph(button);
dv.paragraph(textArea);
dv.paragraph(container);

}
main();
```

```dataviewjs 
const main = async _ => {


const devColor = true;
const dataview_class_identifier = "block-language-dataviewjs";

let bc = "background-color"
if (!devColor) { bc = ""; };

function time_zone(ctime)
{
	if (!ctime) ctime = "2022-01-01"
	let date = new Date(ctime);
	const offset = date.getTimezoneOffset();
	date = new Date(date.getTime() - (offset*60*1000));
	return date.toISOString().split('T')[0];
}


// ADD PAGES

let dv_div = this.container;
let pages = dv.pages('"🗄️scratchpad"').sort(k => k.file.frontmatter.ctime, 'desc');
// pages = pages.slice(0, 50);
let pList = []
let pTime = []
let yesterday_thingy = "000";

let yesterday = new Date();
yesterday.setDate(yesterday.getDate() - 1);

for (let i=0; i<pages.length; i++) {
	const file = await dv.io.load(pages[i].file.path);
	dv.paragraph(file);
	pList.push(dv_div.lastChild);
	dv_div.removeChild(dv_div.lastChild);
	
	
	let time = pages[i].file.frontmatter.ctime;
	if (time) {
		let [year, month, day] = time.split("T")[0].split("-");
		pTime.push(`${day}/${month}/${year}`);
		if (time_zone(yesterday) === time.split("T")[0]) 
			yesterday_thingy = `${day}/${month}/${year}`
	} else {
		pTime.push("undefined");
	}
}


// CUSTOMIZING

const textToLink = (path, text) => `<a aria-label-position="top" aria-label="${path}" data-href="${path}" href="${path}" class="internal-link" target="_blank" rel="noopener">${text}</a>`

function page_component(color, page, page_object) {
	let container = document.createElement('div');
	container.style.cssText = `position:relative; background-color: rgb(28, 33, 38); padding: 5px 0 5px 20px; margin-bottom: 10px; box-shadow: 0px 0px 2px 2px rgba(0, 0, 0, 0.5); border-radius: 1px; overflow: hidden; border: 2px white solid; border-width: 0px 0px 0px 0px; font-size: 1em;`;
	
	let link_style = 
	`position: absolute; width: 8px; height: 100%; background-color: rgb(100, 100, 100); left: 0px; top: 0px;`
	let linkHTML = textToLink(page.file.path, `<div style="${link_style}"></div>`);
	let link_div = document.createElement('div');
	
	container.innerHTML = linkHTML + container.innerHTML;
	
	let span_container = page_object.querySelector('span pre').parentNode;
	if (span_container.children.length > 1) {
		span_container.children[1].style.marginTop = 0;
		span_container.lastChild.style.marginBottom = 0;
	}
	page_object.style.margin = 0;
	
	container.appendChild(page_object);
	
	return container;
}

let current_time = "000"

for (let i=0; i<pList.length; i++) {
	if (current_time !== pTime[i]) {
		dv.span(`<span style='color: ${pTime[i] === yesterday_thingy ? "white" : "grey"}; ${pTime[i] === yesterday_thingy ? "background-color: rgb(255, 255, 0, 0.2)" : "background-color: rgb(0, 0, 0, 0.2)"}; padding: 0 5px; border-radius: 5px 5px 0 0'>` + pTime[i] + "</span>");
		current_time = pTime[i];
	}
	let component = page_component(200*i/pList.length+50, pages[i], pList[i]);
	dv.span(component);
}


};
main();
```