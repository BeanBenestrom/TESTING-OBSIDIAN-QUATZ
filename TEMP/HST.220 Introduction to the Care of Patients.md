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

catalog [HST.220](http://student.mit.edu/catalog/mHSTa.html#HST.220)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4009_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4009_0">Permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4009_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4009_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Provides an introduction to the care of patients through opportunities to observe and participate in doctor-patient interaction in clinical settings and a longitudinal preceptorship experience with HST alumni physicians. Students are exposed to some of the practical realities of providing patient care. Topics include basic interviewing; issues of ethics, bias, and confidentiality; and other aspects of the doctor-patient relationship. The introductory session is held at HMS or Massachusetts General Hospital and the preceptorships are at several Harvard hospitals in Boston. Requirements include attendance at the introductory session and meetings scheduled with the preceptor.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4009_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4009_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4009_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
