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
prereq: Must apply to the Graduate Consortium in Women's Studies
coreq: None.
---

catalog [WGS.600](http://student.mit.edu/catalog/mWGSa.html#WGS.600)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4290_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4290_0">Must apply to the Graduate Consortium in Women's Studies</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4290_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4290_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Addresses the main challenges faced by dissertation writers: isolation, writing schedules, and cogent arguments. Opportunity for members to exchange ideas and experiences, learn general principles of academic argument, and receive feedback. Open to graduate students in all phases of dissertation writing. Meets bi-weekly, spans Fall and Spring terms. Limited to 10.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4290_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4290_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4290_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
