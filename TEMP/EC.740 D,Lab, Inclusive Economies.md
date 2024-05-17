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

catalog [EC.740](http://student.mit.edu/catalog/mECa.html#EC.740)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3870_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3870_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3870_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3870_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Explores how innovations and market mechanisms can benefit humanity by rallying impact investments, engaging participants cooperatively, boosting equity and resilience, and broadening prosperity. Examines the ideas behind, and actions towards, multiple inclusive economic mechanisms and approaches. Students review and analyze the competing worldviews and historical pathways that led to the current dominant economic modalities, and both theoretical and empirical criticisms. Includes case studies developing alternative opportunities, modifications, and/or improvements to crafting circular economies and reinforcing local economies. Team projects focus on the facilitation of inclusive economy models in partnership with communities in Latin America or Africa. Optional project-focused travel may be available over IAP. Limited to 12.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3870_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3870_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3870_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
