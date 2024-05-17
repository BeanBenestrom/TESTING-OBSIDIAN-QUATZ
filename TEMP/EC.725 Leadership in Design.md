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

catalog [EC.725](http://student.mit.edu/catalog/mECa.html#EC.725)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3868_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3868_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3868_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3868_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Places special focus on team capacity building and the communication skills critical to design leadership. Multidisciplinary teams work on semester-long projects in collaboration with international organizations, field practitioners, and experts, building team and leadership skills used to address problems faced by underserved communities while implementing design, experimentation, and hands-on prototyping processes. Topics covered include human-centered design, design for affordability and remote manufacturing, sustainability, and strategies for working effectively with international partners. Limited to 20 students in the Gordon Engineering Leadership Program.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3868_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3868_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3868_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
