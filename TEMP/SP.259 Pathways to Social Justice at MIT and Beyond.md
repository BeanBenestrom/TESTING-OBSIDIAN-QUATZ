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

catalog [SP.259](http://student.mit.edu/catalog/mSPa.html#SP.259)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4227_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4227_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4227_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4227_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">This course explores student pathways to support social change and social justice efforts within the greater Boston region and how students can be agents of change throughout their lives. Students are introduced to ethical, reciprocal, and community-informed approaches to creating social change through readings, lectures, class discussions, critical reflection, and direct service experiences with local community organizations. This course also aims to create a supportive community for undergraduate students to build a network of thoughtful MIT stakeholders dedicated to creating social good in the world. Subject offered by the PKG Public Service Center. Subject can count toward the 6-unit discovery-focused credit limit for first-year students.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4227_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4227_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4227_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
