---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: graduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/7.05 General Biochemistry> and permission of instructor"
coreq: "None."
---

catalog [HST.111](http://student.mit.edu/catalog/mHSTa.html#HST.111)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3990_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3990_0">[[🎓Universities/MIT/7.05 General Biochemistry | 7.05]] and permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3990_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3990_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Considers the normal physiology of the kidney and the pathophysiology of renal disease. Renal regulation of sodium, potassium, acid, and water balance are emphasized as are the mechanism and consequences of renal failure. Included also are the pathology and pathophysiology of clinical renal disorders such as acute and chronic glomerulonephritis, pyelonephritis, and vascular disease. New molecular insights into transporter mutations and renal disease are discussed. Only HST students may register under HST.110, graded P/D/F. Enrollment limited.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3990_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3990_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3990_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
