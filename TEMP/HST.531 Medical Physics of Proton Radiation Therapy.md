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

catalog [HST.531](http://student.mit.edu/catalog/mHSTa.html#HST.531)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4014_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4014_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4014_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4014_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Acceleration of protons for radiation therapy; introduction into advanced techniques such as laser acceleration and dielectric wall acceleration. Topics include the interactions of protons with the patient, Monte Carlo simulation, and dose calculation methods; biological aspects of proton therapy, relative biological effectiveness (RBE), and the role of contaminating neutrons; treatment planning and treatment optimization methods, and intensity-modulated proton therapy (IMPT); the effect of organ motion and its compensation by use of image-guided treatment techniques; general dosimetry and advanced <i>in-vivo</i> dosimetry methods, including PET/CT and prompt gamma measurements. Outlook into therapy with heavier ions. Includes practical demonstrations at the Proton Therapy Center of the Massachusetts General Hospital.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4014_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4014_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4014_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
