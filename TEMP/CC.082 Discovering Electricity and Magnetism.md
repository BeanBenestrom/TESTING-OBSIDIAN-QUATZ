---
tags:
  - course
ctime: 2024-04-18T00:19:28
mstime: 2024-04-18T00:19:28
level: undergraduate
subject: 
university: mit
completion: open
percentage: 0
prereq: None.
coreq: None.
---

catalog [CC.082](http://student.mit.edu/catalog/mCCa.html#CC.082)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq148_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq148_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq148_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq148_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">In this seminar, students discover some of the concepts covered in 8.022 from the perspective of a practicing physicist. Employs vector calculus as an alternative tool for problem solving, and introduces the relativistic origin of magnetism. We will meet twice weekly to discuss these concepts as well as to work together on more advanced kinds of problems. Aims to further engage students already interested in majoring in physics, as well as those who wish simply to discover what physics has to offer. Subject can count toward the 6-unit discovery-focused credit limit for first-year students. Limited to students enrolled in Concourse.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq148_0`, {timeout:5});
COURSE_MODULE.evaluate_req("148_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("148_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
