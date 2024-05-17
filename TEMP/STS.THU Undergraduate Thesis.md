---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: undergraduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/STS.THT Undergraduate Thesis Tutorial>"
coreq: "None."
---

catalog [STS.THU](http://student.mit.edu/catalog/mSTSa.html#STS.THU)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4210_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4210_0">[[🎓Universities/MIT/STS.THT Undergraduate Thesis Tutorial | STS.THT]]</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4210_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4210_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Completion of work of the senior major thesis under the supervision of a faculty tutor. Includes gathering materials, preparing draft chapters, giving an oral presentation of thesis progress to faculty evaluators early in the term, and writing and revising the final text. Students meet at the end of the term with faculty evaluators to discuss the successes and limitations of the project. Required of all candidates for an STS degree.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4210_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4210_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4210_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
