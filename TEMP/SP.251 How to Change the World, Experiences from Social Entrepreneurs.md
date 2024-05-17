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

catalog [SP.251](http://student.mit.edu/catalog/mSPa.html#SP.251)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4219_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4219_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4219_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4219_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Every week, students meet a new role model who demonstrates what it means to change the world through social entrepreneurship. Students meet individual entrepreneurs, get immersed in the ecosystem that supports them, and visit MIT labs and startups in the Cambridge innovation community. Each session covers an aspect of social entrepreneurship, from identifying opportunities for change to market fit to planning for scale. Through these speakers and field trips, students gain a greater understanding of how technology-based, impactful solutions can address global challenges. Students learn to identify and address social and environmental problems and understand the relevance of this work for their time at MIT. They will see how to bring their ideas to fruition and extend their ties with the Solve community. Subject can count toward the 6-unit discovery-focused credit limit for first year-students. Limited to 25; preference to first-year students.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4219_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4219_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4219_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
