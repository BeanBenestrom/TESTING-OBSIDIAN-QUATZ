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

catalog [IDS.522](http://student.mit.edu/catalog/mIDSa.html#IDS.522)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4052_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4052_0">Permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4052_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4052_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Project-based seminar reviews recent developments in energy conversion and storage technologies. Merits of alternative technologies are debated based on their environmental performance and cost, and their potential improvement and scalability. Project teams develop qualitative insights, quantitative models, and interactive visualization tools to inform the future development of technologies. Models may probe how the impact of a technology depends on assumptions about future advancements in performance, and how quantitative performance targets can be estimated to inform investment and design decisions. Other projects may develop models to inform rational investments in a portfolio of technologies based on economic and environmental performance and scalability constraints. Both information-based (e.g., software and codified practices) and physical technologies will be discussed.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4052_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4052_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4052_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
