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
prereq: None.
coreq: None.
---

catalog [HST.500](http://student.mit.edu/catalog/mHSTa.html#HST.500)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4012_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4012_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4012_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4012_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Provides a framework for mapping research topics at the intersection of medicine and engineering/physics in the Harvard-MIT community and covers the different research areas in MEMP (for example, regenerative biomedical technologies, biomedical imaging and biooptics). Lectures provide fundamental concepts and consider what's hot, and why, in each area. Training in scientific proposal writing (thesis proposals, fellowship applications, or research grant applications) through writing workshops. Topics include how to structure a novel research project, how to position research within the scientific community, how to present preliminary data effectively, and how to give and respond to peer reviews.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4012_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4012_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4012_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
