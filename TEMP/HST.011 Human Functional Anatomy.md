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

catalog [HST.011](http://student.mit.edu/catalog/mHSTa.html#HST.011)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3979_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3979_0">Permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3979_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3979_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Lectures, detailed laboratory dissections, and prosections provide a thorough exploration of the gross structure and function of the human body. Fundamental principles of bioengineering are employed to promote analytical approaches to understanding the body's design. The embryology of major organ systems is presented, together with certain references to phylogenetic development, as a basis for comprehending anatomical complexity. Correlation clinics stress both normal and abnormal functions of the body and present evolving knowledge of genes responsible for normal and abnormal anatomy. Lecturers focus on current problems in organ system research. Only HST students may register under HST.010, graded P/D/F. Lab fee. Enrollment restricted to graduate students.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3979_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3979_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3979_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
