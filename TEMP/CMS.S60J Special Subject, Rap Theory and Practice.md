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

catalog [CMS.S60[J]](http://student.mit.edu/catalog/mCMSa.html#CMS.S60), [21L.S60[J]](http://student.mit.edu/catalog/m21La.html#21L.S60), [CMS.S96](http://student.mit.edu/catalog/mCMSa.html#CMS.S96)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq105_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq105_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq105_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq105_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">To gain a deeper understanding of rap, students engage in the full process of creating rap music, including composing lyrics, recording, performing, and creating an EP length album. Existing rap music is studied, selected lyrics are analyzed, and possible reasons for the structure and success of different songs are presented in case studies. Students analyze rap songs, reflect on their own weekly activities in writing and present their work in class by playing recordings, performing and responding to each other in workshop discussions. Licensed for Spring 2024 by the Committee on Curricula. Limited to 10.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq105_0`, {timeout:5});
COURSE_MODULE.evaluate_req("105_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("105_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
