---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: graduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/1.260J Logistics Systems>"
coreq: "None."
---

catalog [SCM.266](http://student.mit.edu/catalog/mSCMa.html#SCM.266)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4243_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4243_0">[[🎓Universities/MIT/1.260J Logistics Systems | SCM.260]]</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4243_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4243_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Provides an in-depth introduction to the fundamental concepts and techniques related to the design, procurement, and management of freight transportation. Examines freight transportation as a bridging function for a firm, considering the physical flow of raw materials and finished goods as well as connections to suppliers and customers. Also covers how freight transportation insulates a firm's core operations from external disruptions and variability of supply and demand.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4243_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4243_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4243_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
