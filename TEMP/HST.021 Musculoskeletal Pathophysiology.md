---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: graduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/HST.031 Human Pathology> and <🎓Universities/MIT/HST.161 Genetics in Modern Medicine>"
coreq: "None."
---

catalog [HST.021](http://student.mit.edu/catalog/mHSTa.html#HST.021)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3981_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3981_0">[[🎓Universities/MIT/HST.031 Human Pathology | HST.030]] and [[🎓Universities/MIT/HST.161 Genetics in Modern Medicine | HST.160]]</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3981_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3981_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Growth and development of normal bone and joints, the biophysics of bone and response to stress and fracture, calcium and phosphate homeostasis and regulation by parathyroid hormone and vitamin D, and the pathogenesis of metabolic bone diseases and disease of connective tissue, joints, and muscles, with consideration of possible mechanisms and underlying metabolic derangements. Only HST students may register under HST.020, graded P/D/F. Enrollment limited; restricted to medical and graduate students.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3981_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3981_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3981_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
