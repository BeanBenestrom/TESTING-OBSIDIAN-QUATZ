---
tags: [course]
ctime: "2024-04-18T00:19:28"
mstime: "2024-04-18T00:19:28"

level: undergraduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "None."
coreq: "<🎓Universities/MIT/18.02 Calculus> and ( <🎓Universities/MIT/CC.010 Seminar I> , <🎓Universities/MIT/CC.011 Seminar II> , or <🎓Universities/MIT/CC.010 Seminar I>)"
---

catalog [CC.1803](http://student.mit.edu/catalog/mCCa.html#CC.1803)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq147_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq147_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq147_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq147_0">[[🎓Universities/MIT/18.02 Calculus | Calculus II (GIR)]] and ( [[🎓Universities/MIT/CC.010 Seminar I | CC.010]] , [[🎓Universities/MIT/CC.011 Seminar II | CC.011]] , or [[🎓Universities/MIT/CC.010 Seminar I | CC.A10]])</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Equivalent to 18.03; see 18.03 for description. Limited to students in Concourse.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq147_0`, {timeout:5});
COURSE_MODULE.evaluate_req("147_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("147_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
