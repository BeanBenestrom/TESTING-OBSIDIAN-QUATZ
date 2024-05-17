---
tags:
  - course
ctime: 2024-04-18T00:19:29
mstime: 2024-04-18T00:19:29
level: graduate
subject: 
university: mit
completion: open
percentage: 0
prereq: None.
coreq: None.
---

catalog [IDS.960](http://student.mit.edu/catalog/mIDSa.html#IDS.960)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4060_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4060_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4060_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4060_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">For Teaching Assistants in IDSS, in cases where teaching assignment is approved for academic credit. Laboratory, tutorial, or classroom teaching under supervision of a faculty member. Credit for this subject may be used to satisfy the teaching requirement for the Doctor of Philosophy in Social and Engineering Systems in IDSS. Otherwise, credit for this subject may not used for any other degree requirement or degree in IDSS.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4060_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4060_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4060_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
