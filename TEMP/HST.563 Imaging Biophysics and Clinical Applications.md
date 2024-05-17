---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: graduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "( <🎓Universities/MIT/8.03 Physics III> and <🎓Universities/MIT/18.03 Differential Equations> ) or permission of instructor"
coreq: "None."
---

catalog [HST.563](http://student.mit.edu/catalog/mHSTa.html#HST.563)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4016_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4016_0">( [[🎓Universities/MIT/8.03 Physics III | 8.03]] and [[🎓Universities/MIT/18.03 Differential Equations | 18.03]] ) or permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4016_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4016_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Introduction to the connections and distinctions among  various imaging modalities (x-ray, optical, ultrasound, MRI, PET, SPECT, EEG), common goals of biomedical imaging, broadly defined target of biomedical imaging, and the current practical and economic landscape of biomedical imaging research. Emphasis on applications of imaging research.  Final project consists of student groups writing mock grant applications for  biomedical imaging research project, modeled after an exploratory National Institutes of Health (NIH) grant application.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4016_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4016_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4016_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
