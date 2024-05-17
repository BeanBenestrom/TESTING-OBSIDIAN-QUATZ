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

catalog [MAS.809](http://student.mit.edu/catalog/mMASa.html#MAS.809)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4097_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4097_0">Permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4097_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4097_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Lectures along with cleanroom lab sessions (in Conformable Decoders' YellowBox) provide exposure to cleanroom processes and microfabrication techniques. Builds practical experience with all five components of the microfabrication techniques, including cleaning, deposition, patterning, etching, and testing. Working in small teams, students complete a midterm project in which they create a video of a microfabrication process demonstrated in the cleanroom. As a final project, students identify a problem that would be tackled with a collective device fabricated in the cleanroom in following semester. Students work throughout the term to develop a class booklet of microfabrication terms. Limited to 10 students, no listeners.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4097_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4097_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4097_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
