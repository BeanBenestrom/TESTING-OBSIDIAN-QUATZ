---
tags: [course]
ctime: "2024-04-18T00:19:28"
mstime: "2024-04-18T00:19:28"

level: undergraduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/AS.411 Leadership Laboratory> or permission of instructor"
coreq: "<🎓Universities/MIT/AS.402 National Security Affairs, Preparation for Active Duty>"
---

catalog [AS.412](http://student.mit.edu/catalog/mASa.html#AS.412)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq15_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq15_0">[[🎓Universities/MIT/AS.411 Leadership Laboratory | AS.411]] or permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq15_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq15_0">[[🎓Universities/MIT/AS.402 National Security Affairs, Preparation for Active Duty | AS.402]]</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Consists of activities classified as advanced leadership experiences that involve the planning and controlling of military activities of the cadet corps, and the preparation and presentation of briefings and other oral and written communications. Also includes interviews, guidance, and information to increase the understanding, motivation, and performance of other cadets. AS.412 is a continuation of AS.411.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq15_0`, {timeout:5});
COURSE_MODULE.evaluate_req("15_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("15_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
