---
tags:
  - course
ctime: 2024-04-18T00:19:28
mstime: 2024-04-18T00:19:28
level: undergraduate
subject: 
university: mit
completion: open
percentage: 0
prereq: None.
coreq: None.
---

catalog [CMS.587[J]](http://student.mit.edu/catalog/mCMSa.html#CMS.587), [11.125[J]](http://student.mit.edu/catalog/m11a.html#11.125)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq77_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq77_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq77_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq77_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">One of two introductory subjects on teaching and learning science and mathematics in a variety of K-12 settings. Topics include student misconceptions, formative assessment, standards and standardized testing, multiple intelligences, and educational technology. Students gain practical experience through weekly visits to schools, classroom discussions, selected readings, and activities to develop a critical and broad understanding of past and current forces that shape the goals and processes of education, and explores the challenges and opportunities of teaching. Students work collaboratively and individually on papers, projects, and in-class presentations. Limited to 25.</font>

```dataviewjs
const main = async _ => {
// --------------------------------
// Load modules
if (!module.exports.utility) dv.executeJs(await dv.io.load("Scripts/utility.js"));
const UTILITY_MODULE = module.exports.utility;
if (!module.exports.course) dv.executeJs(await dv.io.load("Scripts/course.js"));
const COURSE_MODULE = module.exports.course;
// Load tp
let tp = this.app.plugins.getPlugin("templater-obsidian").templater.current_functions_object;
if (!tp) { dv.paragraph("<font style='color: red'>tp not loaded!</font>"); return; }
// Evaluate
await UTILITY_MODULE.waitForElements(`#m_prereq77_0`, {timeout:5});
COURSE_MODULE.evaluate_req("77_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("77_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
