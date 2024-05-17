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

catalog [STS.088](http://student.mit.edu/catalog/mSTSa.html#STS.088)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4204_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4204_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4204_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4204_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Covers historical, cultural, and ethical dimensions of engineering in Africa. Focuses on construction of big projects like cities, hydroelectricity dams, roads, railway lines, ports and harbors, transport and communication, mines, industrial processing plant, and plantations. Explores the contributions of big capital, engineers, politicians, and ordinary people. Emphasizes how local culture, politics, labor, and knowledge affect engineering.  Also focuses on environmental and cultural impact assessment. Prepares students who wish to work or study in Africa and the Global South. Enrollment limited.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4204_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4204_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4204_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
