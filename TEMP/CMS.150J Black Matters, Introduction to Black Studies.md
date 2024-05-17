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

catalog [CMS.150[J]](http://student.mit.edu/catalog/mCMSa.html#CMS.150), [24.912[J]](http://student.mit.edu/catalog/m24b.html#24.912), [21H.106[J]](http://student.mit.edu/catalog/m21Ha.html#21H.106), [21L.008[J]](http://student.mit.edu/catalog/m21La.html#21L.008), [21W.741[J]](http://student.mit.edu/catalog/m21Wa.html#21W.741), [WGS.190[J]](http://student.mit.edu/catalog/mWGSa.html#WGS.190)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq38_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq38_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq38_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq38_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Interdisciplinary survey of people of African descent that draws on the overlapping approaches of history, literature, anthropology, legal studies, media studies, performance, linguistics, and creative writing. Connects the experiences of African-Americans and of other American minorities, focusing on social, political, and cultural histories, and on linguistic patterns. Includes lectures, discussions, workshops, and required field trips that involve minimal cost to students.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq38_0`, {timeout:5});
COURSE_MODULE.evaluate_req("38_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("38_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
