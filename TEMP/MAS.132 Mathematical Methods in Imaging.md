---
tags:
  - course
ctime: 2024-04-18T00:19:29
mstime: 2024-04-18T00:19:29
level: undergraduate
subject: 
university: mit
completion: open
percentage: 0
prereq: Permission of instructor
coreq: None.
---

catalog [MAS.132](http://student.mit.edu/catalog/mMASa.html#MAS.132), [MAS.532](http://student.mit.edu/catalog/mMASa.html#MAS.532)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4080_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4080_0">Permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4080_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4080_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Surveys the landscape of imaging techniques and develops skills for conducting imaging research. Reviews technical and social aspects of the evolving camera culture and considers its role in transforming social interactions, reshaping businesses, and influencing communities worldwide. Explores innovative protocols for sharing and consumption of visual media, as well as novel hardware and software tools based on advanced lenses, digital illumination, modern sensors, and emerging image-analysis algorithms. Students taking graduate version complete additional assignments.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4080_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4080_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4080_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
