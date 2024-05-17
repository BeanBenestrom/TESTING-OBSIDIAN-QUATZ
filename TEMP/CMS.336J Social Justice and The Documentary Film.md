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

catalog [CMS.336[J]](http://student.mit.edu/catalog/mCMSa.html#CMS.336), [21W.786[J]](http://student.mit.edu/catalog/m21Wb.html#21W.786), [CMS.836](http://student.mit.edu/catalog/mCMSa.html#CMS.836)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq51_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq51_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq51_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq51_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Explores the history and current state of social-issue documentary. Examines how cultural and political upheaval and technological change have converged at different moments to bring about new waves of activist documentary film production. Particular focus on films and other non-fiction media of the present and recent past. Students screen and analyze a series of key films and work in groups to produce their own short documentary using digital video and computer-based editing. Students taking graduate version complete additional assignments. Limited to 18.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq51_0`, {timeout:5});
COURSE_MODULE.evaluate_req("51_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("51_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
