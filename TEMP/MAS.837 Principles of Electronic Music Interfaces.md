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

catalog [MAS.837](http://student.mit.edu/catalog/mMASa.html#MAS.837)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4101_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4101_0">Permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4101_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4101_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Explores the ways in which electronic music is controlled and performed. A solid historical perspective is presented, tracing the development of various families of electronic musical controllers and instruments from their genesis in the late 1800s onwards. Design principles and engineering detail are also given for various current and classic controllers. Evolving issues in the control of computer music for live performance and interactive installations are discussed, including computer mapping of sensor signals and transduced gesture onto sound, music, and other media. Weekly reading assignments are given, and a final project or paper is required.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4101_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4101_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4101_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
