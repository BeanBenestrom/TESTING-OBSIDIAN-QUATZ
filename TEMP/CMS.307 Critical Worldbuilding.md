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

catalog [CMS.307](http://student.mit.edu/catalog/mCMSa.html#CMS.307), [CMS.807](http://student.mit.edu/catalog/mCMSa.html#CMS.807)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq43_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq43_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq43_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq43_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Studies the design and analysis of invented (or constructed) worlds for narrative media, such as television, films, comics, and literary texts.  Provides the practical, historical and critical tools with which to understand the function and structure of imagined worlds.  Examines world-building strategies in the various media and genres in order to develop a critical and creative repertoire.  Participants create their own invented worlds. Students taking graduate version complete additional assignments. Limited to 13.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq43_0`, {timeout:5});
COURSE_MODULE.evaluate_req("43_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("43_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
