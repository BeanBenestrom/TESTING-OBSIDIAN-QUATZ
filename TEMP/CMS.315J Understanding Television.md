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
prereq: One subject in Literature or Comparative Media Studies
coreq: None.
---

catalog [CMS.315[J]](http://student.mit.edu/catalog/mCMSa.html#CMS.315), [21L.432[J]](http://student.mit.edu/catalog/m21La.html#21L.432), [CMS.915](http://student.mit.edu/catalog/mCMSa.html#CMS.915)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq48_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq48_0">One subject in Literature or Comparative Media Studies</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq48_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq48_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">A cultural approach to television's evolution as a technology and system of representation. Considers television as a system of storytelling and mythmaking, and as a cultural practice studied from anthropological, literary, and cinematic perspectives. Focuses on prime-time commercial broadcasting, the medium's technological and economic history, and theoretical perspectives. Considerable television viewing and readings in media theory and cultural interpretation are required. Previously taught topics include American Television: A Cultural History. Students taking graduate version complete additional assignments.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq48_0`, {timeout:5});
COURSE_MODULE.evaluate_req("48_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("48_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
