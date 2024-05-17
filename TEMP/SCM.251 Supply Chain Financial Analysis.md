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
coreq: <🎓Universities/MIT/1.260J Logistics Systems>
---

catalog [SCM.251](http://student.mit.edu/catalog/mSCMa.html#SCM.251)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4234_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4234_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4234_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4234_0">[[🎓Universities/MIT/1.260J Logistics Systems | SCM.260]]</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Explores the linkages between supply chain management and corporate finance. Emphasizes how the supply chain creates value for both the shareholders of the company and for the stakeholders affected by the company's operations. Sessions combine lectures and data-rich cases from the manufacturer, distributor, and retailer perspective. Topics include accounting fundamentals, financial analysis, activity-based costing, working capital management, cash flow projections, capital budgeting, and sustainability.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4234_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4234_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4234_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
