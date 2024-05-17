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

catalog [HST.147](http://student.mit.edu/catalog/mHSTa.html#HST.147)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3993_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3993_0">Permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3993_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3993_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">First-year graduate level intensive subject in human biochemistry and physiological chemistry that focuses on intermediary metabolism, structures of key intermediates and enzymes important in human disease. Subject is divided into four areas: carbohydrates, lipids, amino acids and nucleic acids. The importance of these areas is underscored with examples from diseases and clinical correlations. Preparatory sessions meet in August. Only HST students may register under HST.146, graded P/D/F. Enrollment limited.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3993_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3993_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3993_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
