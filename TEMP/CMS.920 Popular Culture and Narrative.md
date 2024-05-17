---
tags:
  - course
ctime: 2024-04-18T00:19:28
mstime: 2024-04-18T00:19:28
level: graduate
subject: 
university: mit
completion: open
percentage: 0
prereq: Permission of instructor
coreq: None.
---

catalog [CMS.920](http://student.mit.edu/catalog/mCMSa.html#CMS.920), [21L.430](http://student.mit.edu/catalog/m21La.html#21L.430)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq125_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq125_0">Permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq125_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq125_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Examines relationships between popular culture and art, focusing on problems of evaluation and audience, and the uses of different media within a broader social context. Typically treats a range of narrative and dramatic works as well as films. Previously taught topics include Elements of Style; Gender, Sexuality and Popular Narrative. Students taking graduate version complete additional assignments. Approved for credit in Women's and Gender Studies when content meets the requirements for subjects in that program. May be repeated for credit with permission of instructor.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq125_0`, {timeout:5});
COURSE_MODULE.evaluate_req("125_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("125_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
