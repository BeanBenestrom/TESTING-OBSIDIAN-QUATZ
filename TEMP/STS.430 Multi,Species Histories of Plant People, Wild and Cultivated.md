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
prereq: None.
coreq: None.
---

catalog [STS.430](http://student.mit.edu/catalog/mSTSb.html#STS.430)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4158_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4158_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4158_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4158_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Examines how centering plants changes our understanding of what it means to be human. Considers how, in response to the naming of the Anthropocene and anxieties over ecological crises, researchers in various fields have turned to plants as central players. Using this as a starting point, explores how researchers have described and re-calibrated relations among plants, humans, and environment, between life and non-life, action and being, subjectivity and autonomy in ways that radically altered ruling epistemologies in a range of disciplines. Looks at how philosophers, farmers, foresters, eco-critics, geographers, botanists, and popular science writers adapted research questions and narratives to incorporate not only plant uses, but plant intelligence and sentience.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4158_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4158_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4158_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
