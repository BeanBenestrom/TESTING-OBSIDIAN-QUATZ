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

catalog [EC.750](http://student.mit.edu/catalog/mECa.html#EC.750), [EC.785](http://student.mit.edu/catalog/mECa.html#EC.785)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3872_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3872_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3872_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3872_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Explores the role innovation can and does play in how humanitarian aid is provided, and how it can impact people, products, and processes. Provides a fundamental background in the history and practice of humanitarian aid. Considers the various ways that design can be used to enhance aid, such as product and system design for affected populations, co-creation with affected populations, and capacity building to promote design by refugees and the displaced. Case studies and projects examine protracted displacement as well as recovery and resettlement, including efforts in Colombia, Lebanon, Nepal, Sudan, and Uganda. Potential for students to travel over the summer to partner communities.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3872_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3872_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3872_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
