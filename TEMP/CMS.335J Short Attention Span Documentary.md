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

catalog [CMS.335[J]](http://student.mit.edu/catalog/mCMSa.html#CMS.335), [21W.790[J]](http://student.mit.edu/catalog/m21Wb.html#21W.790), [21W.890](http://student.mit.edu/catalog/m21Wb.html#21W.890)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq50_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq50_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq50_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq50_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Focuses on the production of short (1- to 5-minute) digital video documentaries: a form of non-fiction filmmaking that has proliferated in recent years due to the ubiquity of palm-sized and mobile phone cameras and the rise of web-based platforms, such as YouTube. Students shoot, edit, workshop and revise a series of short videos meant to engage audiences in a topic, introduce them to new ideas, and/or persuade them. Screenings and discussions cover key principles of documentary film - narrative, style, pace, point of view, argument, character development - examining how they function and change in short format. Students taking graduate version complete additional assignments. Limited to 16.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq50_0`, {timeout:5});
COURSE_MODULE.evaluate_req("50_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("50_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
