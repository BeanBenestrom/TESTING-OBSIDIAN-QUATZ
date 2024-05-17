---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: graduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/EM.425 Research Seminar on Engineering Projects and Teamwork> or permission of instructor"
coreq: "None."
---

catalog [EM.426](http://student.mit.edu/catalog/mEMa.html#EM.426)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3907_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3907_0">[[🎓Universities/MIT/EM.425 Research Seminar on Engineering Projects and Teamwork | EM.425]] or permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3907_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3907_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Explores agent-based models and simulation for engineering project management. Students build and validate models of engineered systems and engineering teamwork, which integrate technology and organization useful during project shaping, ideation, planning, control, adaptation, and lessons learned. Models capture phenomena discussed in EM.425 and are simulated to forecast performance such as feasible scope, human activity, interactions, cost, schedule, quality, and risks. In the first half, students build a model and agent-based simulation from scratch. In the second half, students work in small teams on either a case modeled using methods introduced in the first half or an extension of said methods to explore a particular engineering phenomenon introduced in the first half.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3907_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3907_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3907_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
