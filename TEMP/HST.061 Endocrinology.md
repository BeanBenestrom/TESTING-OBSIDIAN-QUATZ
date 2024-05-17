---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: graduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/7.012 Introductory Biology> , <🎓Universities/MIT/7.05 General Biochemistry> , and permission of instructor"
coreq: "None."
---

catalog [HST.061](http://student.mit.edu/catalog/mHSTa.html#HST.061)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3985_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3985_0">[[🎓Universities/MIT/7.012 Introductory Biology | Biology (GIR)]] , [[🎓Universities/MIT/7.05 General Biochemistry | 7.05]] , and permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3985_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3985_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Physiology and pathophysiology of the human endocrine system. Three hours of lecture and section each week concern individual parts of the endocrine system. Topics include assay techniques, physiological integration, etc. At frequent clinic sessions, patients are presented who demonstrate clinical problems considered in the didactic lectures. Only HST students may register under HST.060, graded P/D/F. Enrollment limited.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3985_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3985_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3985_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
