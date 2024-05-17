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

catalog [STS.040](http://student.mit.edu/catalog/mSTSa.html#STS.040)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4194_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4194_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4194_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4194_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Inspires students to think about production chains in ways that reflect their impact on the environment, labor practices, and human health. Examines how commodities connect distant places through a chain of relationships, and link people, e.g., enslaved African producers with middle-class American consumers, and Asian factory workers with Europeans taking a holiday on the beach. Studies how mass production and mass demand for commodities, such as real estate, bananas, rubber, corn, and beef, in the 20th century changed the way people worked, lived, and saw themselves as they adopted new technologies to produce and consume in radically different ways from their parents and grandparents. Assignments include creation of a board game for buying and selling real estate in Boston, a two-minute mini-documentary, and an article on a commodity and country. Limited to 25.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4194_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4194_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4194_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
