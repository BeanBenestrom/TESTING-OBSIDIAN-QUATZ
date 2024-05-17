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

catalog [CMS.619[J]](http://student.mit.edu/catalog/mCMSa.html#CMS.619), [WGS.111[J]](http://student.mit.edu/catalog/mWGSa.html#WGS.111)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq94_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq94_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq94_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq94_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Examines representations of race, gender, and sexual identity in the media. Considers issues of authorship, spectatorship, and the ways in which various media (film, television, print journalism, advertising) enable, facilitate, and challenge these social constructions in society. Studies the impact of new media and digital media through analysis of gendered and racialized language and embodiment online in blogs and vlogs, avatars, and in the construction of cyberidentities. Provides introduction to feminist approaches to media studies by drawing from work in feminist film theory, cultural studies, gender and politics, and cyberfeminism.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq94_0`, {timeout:5});
COURSE_MODULE.evaluate_req("94_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("94_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
