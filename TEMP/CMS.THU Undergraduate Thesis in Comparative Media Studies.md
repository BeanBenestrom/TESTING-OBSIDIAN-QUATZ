---
tags: [course]
ctime: "2024-04-18T00:19:28"
mstime: "2024-04-18T00:19:28"

level: undergraduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/CMS.THT Comparative Media Studies Pre,Thesis Tutorial>"
coreq: "None."
---

catalog [CMS.THU](http://student.mit.edu/catalog/mCMSa.html#CMS.THU)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq110_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq110_0">[[🎓Universities/MIT/CMS.THT Comparative Media Studies Pre,Thesis Tutorial | CMS.THT]]</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq110_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq110_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">The CMS Undergraduate Thesis is a substantial research project or comparable exercise. A written thesis ranges in length from 35 to 50 pages. Digital projects are assessed on the quality of research and argumentation, as well as presentation, and must include a substantial written component. Student gives an oral presentation of his/her thesis at the end of the term. Thesis is not required for CMS majors.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq110_0`, {timeout:5});
COURSE_MODULE.evaluate_req("110_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("110_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
