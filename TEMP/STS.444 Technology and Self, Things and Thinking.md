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

catalog [STS.444](http://student.mit.edu/catalog/mSTSb.html#STS.444), [STS.044](http://student.mit.edu/catalog/mSTSa.html#STS.044)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4162_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4162_0">Permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4162_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4162_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Explores emotional and intellectual impact of objects. The growing literature on cognition and “things” cuts across anthropology, history, social theory, literature, sociology, and psychology and is of great relevance to science students. Examines the range of theories, from Mary Douglas in anthropology to D.W. Winnicott in psychoanalytic thinking, that underlies “thing” or “object” analysis. Students taking graduate version complete additional assignments. Limited to 15; no listeners.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4162_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4162_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4162_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
