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

catalog [CMS.300](http://student.mit.edu/catalog/mCMSa.html#CMS.300), [CMS.841](http://student.mit.edu/catalog/mCMSa.html#CMS.841)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq39_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq39_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq39_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq39_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Introduction to the interdisciplinary study of videogames as texts through an examination of their cultural, educational, and social functions in contemporary settings. Students play and analyze videogames while reading current research and theory from a variety of sources in the sciences, social sciences, humanities, and industry. Assignments focus on game analysis in the context of the theories discussed in class. Includes regular reading, writing, and presentation exercises. No prior programming experience required. Students taking graduate version complete additional assignments. Limited to 20.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq39_0`, {timeout:5});
COURSE_MODULE.evaluate_req("39_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("39_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
