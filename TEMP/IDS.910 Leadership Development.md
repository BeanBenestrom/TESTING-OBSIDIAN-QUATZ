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
prereq: Permission of instructor
coreq: None.
---

catalog [IDS.910](http://student.mit.edu/catalog/mIDSa.html#IDS.910)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4054_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4054_0">Permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4054_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4054_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Seminar environment created to develop leadership capabilities, and to take advantage of leadership opportunities. An initial Outward Bound experience builds trust, teamwork and communications. Readings and assignments emphasize the characteristics of desired leadership skills. Global leaders participate in the Leadership Lunch series to share their experiences and recommendations. Discussions explore leadership development. Culminates in a personal leadership plan. Restricted to entering students in the Technology and Policy program or instructor permission.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4054_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4054_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4054_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
