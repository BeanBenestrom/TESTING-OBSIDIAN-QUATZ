---
tags: [course]
ctime: "2024-04-18T00:19:28"
mstime: "2024-04-18T00:19:28"

level: graduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/SCM.254 Analytical Methods for Supply Chain Management II> or permission of instructor"
coreq: "<🎓Universities/MIT/6.C01 Modeling with Machine Learning, from Algorithms to Applications>"
---

catalog [SCM.C51](http://student.mit.edu/catalog/mCGa.html#CG.080)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq31_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq31_0">[[🎓Universities/MIT/SCM.254 Analytical Methods for Supply Chain Management II | SCM.254]] or permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq31_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq31_0">[[🎓Universities/MIT/6.C01 Modeling with Machine Learning, from Algorithms to Applications | 6.C51]]</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Building on core material in 6.C51, applies selected machine learning models to build practical, data-driven implementations addressing key business problems in supply chain management. Discusses challenges that typically arise in these practical implementations. Addresses relevant elements for large scale productionalization and monitoring of machine learning models in practice. Students cannot receive credit without simultaneous completion of the core subject 6.C51.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq31_0`, {timeout:5});
COURSE_MODULE.evaluate_req("31_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("31_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
