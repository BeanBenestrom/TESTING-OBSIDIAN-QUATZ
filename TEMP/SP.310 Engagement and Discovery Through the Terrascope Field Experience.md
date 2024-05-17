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

catalog [SP.310](http://student.mit.edu/catalog/mSPa.html#SP.310)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4228_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4228_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4228_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4228_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Each spring, first-year students in the Terrascope Learning Community spend a week exploring a sustainability-related problem in an off-campus site. During the trip, students engage with communities affected by the problem and people taking a wide range of approaches to address it. In this course, students will integrate and communicate their experience from the trip, with the aim of deepening their consideration of the year's problem and how the field experience impacts their thoughts about their own pathways through MIT and beyond. Students will learn about best practices and opportunities for civic engagement related to the year's topic, and they will explore ways of communicating their learnings from the field experience. Limited to first-year students participating in the Terrascope spring break field experience.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4228_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4228_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4228_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
