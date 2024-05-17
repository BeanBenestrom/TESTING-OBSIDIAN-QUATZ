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

catalog [CMS.702](http://student.mit.edu/catalog/mCMSa.html#CMS.702), [CMS.802](http://student.mit.edu/catalog/mCMSa.html#CMS.802)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq104_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq104_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq104_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq104_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Focuses on a number of qualitative social science methods including interviewing, participant observation, focus groups, cultural probes, and visual sociology. Primary emphasis on understanding and learning concrete techniques that can be evaluated and utilized in any given project. Data organization and analysis will be addressed. Several advanced critical thematics are also covered, including ethics, reciprocity, "studying up," and risk. Students taking graduate version complete additional assignments.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq104_0`, {timeout:5});
COURSE_MODULE.evaluate_req("104_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("104_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
