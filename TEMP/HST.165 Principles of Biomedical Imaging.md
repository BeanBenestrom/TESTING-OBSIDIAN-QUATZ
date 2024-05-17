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

catalog [HST.165](http://student.mit.edu/catalog/mHSTa.html#HST.165)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3997_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3997_0">Permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3997_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3997_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Reviews fundamental principles and techniques underlying modern biomedical imaging, as well as their application in modern medicine. Particular emphasis on magnetic resonance; also covers ultrasound, computed tomography, positron emission tomography and optical techniques. Didactic lectures accompanied by problem sets and experiments with portable magnetic resonance systems and ultrasound systems. Focuses on the quantitative aspects of biomedical imaging and requires a knowledge of differential equations, MATLAB, and intermediate-level physics. Only HST students may register under HST.164, P/D/F. Restricted to HST students.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3997_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3997_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3997_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
