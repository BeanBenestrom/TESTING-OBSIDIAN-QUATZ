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

catalog [MAS.600](http://student.mit.edu/catalog/mMASa.html#MAS.600)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4088_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4088_0">Permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4088_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4088_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Covers principles underlying current and future technologies for cognitive, emotional and physical augmentation. Focuses on using anatomical, biomechanical, neuromechanical, biochemical and neurological models of the human body to guide the designs of augmentation technology for persons with either unusual or normal physiologies that wish to extend their cognitive, emotion, social or physical capability to new levels.   Topics include robotic exoskeletons and powered orthoses, external limb prostheses, neural implant technology, social-emotional prostheses, and cognitive prostheses. Requires student presentations, critiques of class readings, and a final project including a publication-quality paper. Enrollment limited.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4088_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4088_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4088_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
