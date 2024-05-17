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

catalog [WGS.224](http://student.mit.edu/catalog/mWGSa.html#WGS.224)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4280_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4280_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4280_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4280_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Explores the politics of reproductive health care delivery in the United States, with a particular focus on how clinical care is shaped by--and, in turn, shapes--social inequality along axes of race and gender. Considers a variety of reproductive health issues from multiple perspectives, drawing on readings from the fields of history, anthropology, sociology, medicine, epidemiology, and law. Develops skills to interrogate how each field conceptualizes and values reproductive health, both explicitly and implicitly. Introduces major conceptual issues foundational to understanding the politics of reproduction. Goes on to cover topics such as the human biofemale reproductive lifecycle and social movements explicitly organized around reproductive health. Limited to 40.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4280_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4280_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4280_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
