---
tags:
  - course
ctime: 2024-04-18T00:19:29
mstime: 2024-04-18T00:19:29
level: undergraduate
subject: 
university: mit
completion: open
percentage: 0
prereq: None.
coreq: None.
---

catalog [SP.252](http://student.mit.edu/catalog/mSPa.html#SP.252)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4220_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4220_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4220_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4220_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Through this course, students will explore careers in medicine and health care. It will also explore potential majors for students looking to go into these different careers, which include physicians, physician-scientists, research scientists, biomedical engineers, bioinformatics analysts, computational biologists, health data scientists, health system managers, and health economists. Majors could include biological engineering, biology, chemical engineering, mechanical engineering, computer science, and more. Allows students to explore how they can have an impact in the field of medicine in a variety of different ways. Exposes students to career paths that are patient-facing (clinical) as well as career paths that are behind the scenes. Includes field trips to nearby labs and companies. Subject can count toward the 6-unit discovery-focused credit limit for first-year students. Limited to 25; preference to first-year students.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4220_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4220_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4220_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
