---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: graduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "( <🎓Universities/MIT/HST.031 Human Pathology> or <🎓Universities/MIT/HST.031 Human Pathology> ) and permission of instructor"
coreq: "None."
---

catalog [HST.091](http://student.mit.edu/catalog/mHSTa.html#HST.091)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3988_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3988_0">( [[🎓Universities/MIT/HST.031 Human Pathology | HST.030]] or [[🎓Universities/MIT/HST.031 Human Pathology | HST.031]] ) and permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3988_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3988_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Normal and pathologic physiology of the heart and vascular system. Emphasis includes hemodynamics, electrophysiology, gross pathology, and clinical correlates of cardiovascular function in normal and in a variety of disease states. Special attention given to congenital, rheumatic, valvular heart disease and cardiomyopathy. Only HST students may register under HST.090, graded P/D/F. Enrollment limited.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3988_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3988_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3988_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
