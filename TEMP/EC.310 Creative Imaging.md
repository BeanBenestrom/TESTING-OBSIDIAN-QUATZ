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
prereq: None.
coreq: None.
---

catalog [EC.310](http://student.mit.edu/catalog/mECa.html#EC.310)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3861_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3861_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3861_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3861_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Focuses on film and digital photography. Develops skill in the use of chemical darkrooms, scanners, digital printers and cameras to create striking still images capable of evoking strong emotional and intellectual responses from a viewer. Emphasizes the interplay between classical chemical and digital techniques and how they can be used to control the use of lighting, color, depth, and composition in an image. Students present their intermediate assignments to the class for critical discussion; at the end of the term, they submit a substantive project presenting their own creative images for critique and evaluation.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3861_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3861_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3861_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
