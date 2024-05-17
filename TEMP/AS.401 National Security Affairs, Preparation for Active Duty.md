---
tags: [course]
ctime: "2024-04-18T00:19:28"
mstime: "2024-04-18T00:19:28"

level: undergraduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/AS.302 Leading People and Effective Communication> or permission of instructor"
coreq: "<🎓Universities/MIT/AS.411 Leadership Laboratory>"
---

catalog [AS.401](http://student.mit.edu/catalog/mASa.html#AS.401)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq12_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq12_0">[[🎓Universities/MIT/AS.302 Leading People and Effective Communication | AS.302]] or permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq12_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq12_0">[[🎓Universities/MIT/AS.411 Leadership Laboratory | AS.411]]</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Designed for college seniors, providing them the foundation to understand their role as military officers in American society. Includes an overview of the complex social and political issues facing the military profession and requires a measure of sophistication commensurate with the senior college level.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq12_0`, {timeout:5});
COURSE_MODULE.evaluate_req("12_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("12_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
