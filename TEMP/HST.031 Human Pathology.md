---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: graduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/7.012 Introductory Biology> , <🎓Universities/MIT/8.01 Physics I> , and permission of instructor"
coreq: "None."
---

catalog [HST.031](http://student.mit.edu/catalog/mHSTa.html#HST.031)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3982_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3982_0">[[🎓Universities/MIT/7.012 Introductory Biology | Biology (GIR)]] , [[🎓Universities/MIT/8.01 Physics I | Physics I (GIR)]] , and permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3982_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3982_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Introduction to the functional structure of normal cells and tissues, pathologic principles of cellular adaptation and injury, inflammation, circulatory disorders, immunologic injury, infection, genetic disorders, and neoplasia in humans. Lectures, conferences emphasizing clinical correlations and contemporary experimental biology. Laboratories with examination of microscopic and gross specimens, and autopsy case studies emphasizing modern pathology practice. Only HST students may register under HST.030, graded P/D/F. Lab fee. Enrollment limited.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3982_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3982_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3982_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
