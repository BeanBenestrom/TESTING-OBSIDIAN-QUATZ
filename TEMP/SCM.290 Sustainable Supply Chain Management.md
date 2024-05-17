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

catalog [SCM.290](http://student.mit.edu/catalog/mSCMa.html#SCM.290)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4253_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4253_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4253_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4253_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Focuses on analyzing the environmental implications of logistics decisions in the supply chain, with special focus on the effect of green transportation, and the new trends in logistics sustainability within the context of growing urbanization and e-commerce. Studies practical alternatives on how to optimize CO2 emissions during last-mile operations by using geo-spatial analysis, and data analytics. Examines the delivery of "fast" and "green" in the new digital era, consumer relationship to sustainable products and services, and environmental costs of fast-shipping e-commerce. Covers supply chain carbon footprint, sustainable transportation, green vehicle routing, fleet assignment, truck consolidation, closed-loop supply chains, reverse logistics, green inventory management, and green consumer behavior.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4253_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4253_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4253_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
