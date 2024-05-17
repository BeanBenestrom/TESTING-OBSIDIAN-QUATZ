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

catalog [CMS.796](http://student.mit.edu/catalog/mCMSa.html#CMS.796)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq115_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq115_0">Permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq115_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq115_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Intensive close study and analysis of historically significant media "texts" that have been considered landmarks or have sustained extensive critical and scholarly discussion. Such texts may include oral epic, story cycles, plays, novels, films, opera, television drama and digital works. Emphasizes close reading from a variety of contextual and aesthetic perspectives. Syllabus varies each year, and may be organized around works that have launched new modes and genres, works that reflect upon their own media practices, or on stories that migrate from one medium to another. At least one of the assigned texts is collaboratively taught, and visiting lectures and discussions are a regular feature of the subject.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq115_0`, {timeout:5});
COURSE_MODULE.evaluate_req("115_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("115_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
