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

catalog [CMS.374[J]](http://student.mit.edu/catalog/mCMSa.html#CMS.374), [4.376[J]](http://student.mit.edu/catalog/m4c.html#4.376), [CMS.877](http://student.mit.edu/catalog/mCMSa.html#CMS.877)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq70_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq70_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq70_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq70_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Exploration of today's extractive economies and the role that artists, media-makers, and transmedia producers play in shaping public perception, individual choices, and movement-building towards sustainability. Traces the contingent geological, material, community, and toxic histories of extracted materials used throughout our built environment, as well as civic resistance and reform that could alter extraction practices. Scaffolded workshops with artists and media producers support students' production of creative documentary and other media projects. Students taking graduate version complete additional assignments.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq70_0`, {timeout:5});
COURSE_MODULE.evaluate_req("70_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("70_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
