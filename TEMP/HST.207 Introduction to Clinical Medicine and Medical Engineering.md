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

catalog [HST.207](http://student.mit.edu/catalog/mHSTa.html#HST.207)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4008_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4008_0">Permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4008_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4008_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Introduction to the intricacies of clinical decision-making through broad exposure to how clinicians think and work in teams. Instruction provided in patient interviewing and physical examination; organizing and communicating clinical information in written and oral forms; and integrating history, physical, and laboratory data with pathophysiologic principles. Attention to the economic, ethical, and sociological issues involved in patient care. Consists of immersive clinical experiences at Massachusetts General Hospital, leveraging extensive educational resources across inpatient clinical floors, ambulatory clinics, procedural/surgical suites, diagnostic testing areas, simulation learning lab, and didactic settings, followed by a focused experience in which students develop a proposal to solve an unmet need identified during their clinical experiences. Equivalent to combination of HST.201 and HST.202. Restricted to HST MEMP students.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4008_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4008_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4008_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
