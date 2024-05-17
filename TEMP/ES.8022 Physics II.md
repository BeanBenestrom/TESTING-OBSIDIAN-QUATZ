---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: undergraduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/8.01 Physics I>"
coreq: "<🎓Universities/MIT/18.02 Calculus>"
---

catalog [ES.8022](http://student.mit.edu/catalog/mESa.html#ES.8022)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3929_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3929_0">[[🎓Universities/MIT/8.01 Physics I | Physics I (GIR)]]</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3929_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3929_0">[[🎓Universities/MIT/18.02 Calculus | Calculus II (GIR)]]</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Equivalent to 8.022; see 8.022 for description. Students complete group projects. Some content is decided by students. Limited to students in ESG.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3929_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3929_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3929_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
