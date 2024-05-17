---
tags:
  - course
ctime: 2024-04-18T00:19:28
mstime: 2024-04-18T00:19:28
level: undergraduate
subject: 
university: mit
completion: open
percentage: 0
prereq: None.
coreq: None.
---

catalog [CC.117[J]](http://student.mit.edu/catalog/mCCa.html#CC.117), [17.05[J]](http://student.mit.edu/catalog/m17a.html#17.05)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq155_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq155_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq155_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq155_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Explores questions of justice and ethics in war by focusing on primary texts of pre-modern works of history, philosophy, literature, and Biblical interpretation. Readings from antiquity include Thucydides, Aristophanes, and Cicero.  Examination of the Biblical tradition of just war, itself informed by the classical tradition, includes readings from early and Medieval Christian and Islamic thinkers and proceeds through the early Renaissance, with the beginning of a formalized doctrine of just war theory. Readings about current ethical dilemmas of war are discussed throughout and are given sustained attention at the end of the term. Preference to Concourse students.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq155_0`, {timeout:5});
COURSE_MODULE.evaluate_req("155_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("155_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
