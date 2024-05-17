---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: graduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/7.05 General Biochemistry> or permission of instructor"
coreq: "None."
---

catalog [HST.035](http://student.mit.edu/catalog/mHSTa.html#HST.035)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3983_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3983_0">[[🎓Universities/MIT/7.05 General Biochemistry | 7.05]] or permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3983_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3983_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Provides a comprehensive overview of human pathology with emphasis on mechanisms of disease and modern diagnostic technologies. Topics include general mechanisms of disease (inflammation, infection, immune injury, transplantation, genetic disorders and neoplasia); pathology of lipids, enzymes, and molecular transporters; pathology of major organ systems; and review of diagnostic tools from surgical pathology to non-invasive techniques such as spectroscopy, imaging, and molecular markers of disease. The objectives of this subject are achieved by a set of integrated lectures and laboratories, as well as a student-driven term project leading to a formal presentation on a medical, socioeconomic, or technological issue in human pathology. Only HST students enrolled in specific degree programs may register under HST.034, graded P/D/F. Credit cannot also be received for HST.030 or HST.031.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3983_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3983_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3983_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
