
# <font style="display: flex; justify-content: center; font-size: 3rem">☁️ THOUGHT QUERY</font>

<br>

```dataviewjs
// Settings

let TAG_QUERY = "-pointer & -scratchpad"

// Button

let buttonColor = "rgb(50, 120, 220)";
let buttonHoverColor = "rgb(50, 120, 220)";
let pressedButtonColor = "rgb(10, 50, 150)";
let pressedSortButtonColor = "rgb(35, 35, 35)";
let buttonWidth = "80px";
let buttonMargin = "10px";

///////////////////////////////////////////////////////////////////////////////

// MODULES

if (!module.exports.query) dv.executeJs(await dv.io.load("Scripts/query.js"));
const QUERY_MODULE = module.exports.query;

// FUNCTIONS

function time_zone(ctime)
{
	if (!ctime) ctime = "2022-01-01"
	let date = new Date(ctime);
	const offset = date.getTimezoneOffset();
	date = new Date(date.getTime() - (offset*60*1000));
	return date.toISOString().split('T')[0];
}

function get_all_status_as_array(files)
{
	let status_array = [];
	for (let i = 0; i < files.length; i++)
	{
		status_array.push(files[i]["status"]);
	}
	return status_array;
}

function createButton(func=null, style=null, text=null, id=null)
{
	let button = document.createElement("BUTTON");
	if (id)    button.setAttribute("id", id);
	if (style) button.style.cssText = style;
	if (text)  button.append(text);
	
	if (func) 
	{
		button.addEventListener('click', function (e) {
			e.stopPropagation();
			func();
			queryFunction();
		});
	}
	
	return button;
	
	// button.style.margin = `0 ${buttonMargin} 0 0`;
	// button.style.width = buttonWidth;
}

function parseTagQuery(queryString) {
	let query = queryString.split(' ');
	query.forEach( (k, i) => { 
		if (k.length < 2) return;
		query[i] = k[0] == '-' ? '-#'+k.slice(1) : '#'+k ;
	});
	return query.join(' ');
}

const C_text = (r, g, b, number) => `<font style="color: rgb(${r}, ${g}, ${b}); font-size: 13px">(${number})`;


const draw = _ => { 

Array.from(this.container.children).slice(1).forEach( k => k.remove() );

// GET ACTUAL QUERY MESSAGE & MAX AMOUNT OF NOTES

let actualQuery = '("☁️Thoughts" or #thought)';
let maxQueySize = dv.pages(actualQuery)
					.where(t => QUERY_MODULE.commonSkip(t.file)).length;
actualQuery = TAG_QUERY == "" ? actualQuery : `${actualQuery} and (${TAG_QUERY})`;


// DRAW NOTES

let pages = dv.pages(actualQuery)                                      // Get thoughts
			.where(t => QUERY_MODULE.commonSkip(t.file))
			.sort(k => k.file.frontmatter.ctime, 'desc');

let querySize = pages.length;
let filteredSize = maxQueySize - querySize;

let groupPages = pages.groupBy(k => dv.date(time_zone(k.file.frontmatter.ctime))); // Group thoughts

dv.table(                                                              // Create table
	[
		`Date ${C_text(50, 200, 50, querySize)}${C_text(130, 30, 40, filteredSize)}`, 
		"Thought", 
		"status"
	],
	groupPages
	.sort(b => b.rows.file.frontmatter.ctime, "desc")
	.map(b => [b.key, b.rows.file.link, get_all_status_as_array(b.rows)])
);

let xxx = setInterval(_ => {
	let table = document.getElementsByClassName("dataview table-view-table");
	if (!table || table.length < 1) return;
	
	table = table[table.length - 1];
	if (!table.parentNode) return;
	table.parentNode.classList.add("thoughts-query");
	clearInterval(xxx);
}, 100);

///////////////////////////////////////////////////////////////////////////////

{
	let pages = dv.pages('"☁️Thoughts" and -#thought')
					.sort(f => f.file.name)
	
	if (pages.length)
	{
		let s = pages.length > 1 ? "s" : "";
		
		dv.header(5, `${pages.length} File${s} in ☁️Thoughts/ missing #thought`)
		dv.list(pages.file.link)
		dv.paragraph("---")
	}
}

///////////////////////////////////////////////////////////////////////////////

{
	let pages = dv.pages('"☁️Thoughts"')
					.where(f => !f.file.frontmatter.ctime)
					.sort(f => f.file.name)
	
	if (pages.length)
	{
		
		let s = pages.length > 1 ? "s" : "";
		
		dv.header(5, `${pages.length} File${s} in ☁️Thoughts/ missing ctime`)
		dv.list(pages.file.link)
		dv.paragraph("---")
	}
}

}

{
	let button = document.createElement("BUTTON");
	button.setAttribute("id", "thoughts-button");
	button.style.margin = `0 ${buttonMargin} 0 0`;
	button.style.width = buttonWidth;
	button.append("Search");
	
	let textBox = document.createElement("INPUT");  
	textBox.setAttribute("type", "text");
	textBox.setAttribute("id", "thoughts-textbox");
	textBox.setAttribute("value", TAG_QUERY);
	textBox.style.width = `calc(100% - ${button.style.width} - ${buttonMargin})`;
	
	button.addEventListener('click', function (e) {
	    e.stopPropagation();
		TAG_QUERY = parseTagQuery(textBox.value);
		draw();
	});
	
	let search = document.createElement("div");
	search.append(button);
	search.append(textBox);
	
	dv.paragraph(search);
}

TAG_QUERY = parseTagQuery(TAG_QUERY);
draw();

// STYLING -----------------------------------------------------------------------

let s = document.getElementById("thoughts-stylesheet");
if (s) s.remove();

let style = `
	@keyframes thoughtsButtonPressed {
	  from {background-color: ${pressedButtonColor};}
	  to {background-color: ${buttonColor};}
	}
	@keyframes thoughtsEmptyKeyFrame { }
	
	#thoughts-button {
		background-color: ${buttonColor};
		animation-name: thoughtsButtonPressed;
		animation-duration: 1s;
	}
	
	#thoughts-button:hover {
		background-color: ${buttonHoverColor};
	}
	
	#thoughts-button:active {
		background-color: ${pressedButtonColor};
		animation-name: thoughtsEmptyKeyFrame;
		animation-duration: 0s;
	}
`;

let styleSheet = document.createElement("style");
styleSheet.id = "thoughts-stylesheet";
styleSheet.innerText = style;
document.head.appendChild(styleSheet);
```