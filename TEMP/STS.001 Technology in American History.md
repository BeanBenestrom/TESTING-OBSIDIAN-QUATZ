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

catalog [STS.001](http://student.mit.edu/catalog/mSTSa.html#STS.001)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4176_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4176_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4176_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4176_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">A survey of America's transition from a rural, agrarian, and artisan society to one of the world's leading industrial powers. Treats the emergence of industrial capitalism: the rise of the factory system; new forms of power, transport, and communication; the advent of the large industrial corporation; the social relations of production; and the hallmarks of science-based industry. Views technology as part of the larger culture and reveals innovation as a process consisting of a range of possibilities that are chosen or rejected according to the social criteria of the time.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4176_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4176_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4176_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
