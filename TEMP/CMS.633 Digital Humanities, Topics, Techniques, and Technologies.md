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

catalog [CMS.633](http://student.mit.edu/catalog/mCMSa.html#CMS.633), [CMS.833](http://student.mit.edu/catalog/mCMSa.html#CMS.833)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq99_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq99_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq99_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq99_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Examines theory and practice of using computational methods in the emerging field of digital humanities. Develops an understanding of key digital humanities concepts such as data representation, digital archives, information visualization, and user interaction through the study of contemporary research in conjunction with working on real-world projects for scholarly, educational, and public needs. Students create prototypes, write design papers, and conduct user studies. Some programming and design experience is helpful but not required.   Students taking graduate version complete additional assignments.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq99_0`, {timeout:5});
COURSE_MODULE.evaluate_req("99_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("99_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
