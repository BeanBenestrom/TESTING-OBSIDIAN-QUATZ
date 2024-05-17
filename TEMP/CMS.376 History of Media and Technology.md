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

catalog [CMS.376](http://student.mit.edu/catalog/mCMSa.html#CMS.376), [CMS.876](http://student.mit.edu/catalog/mCMSa.html#CMS.876)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq72_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq72_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq72_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq72_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Surveys the interrelated histories of communications media and technological development, from the emergence of 19th-century forms of mass print media and telegraphy, to sound capture and image-based forms (e.g., film, radio, and television), to the shift from analog to digital cultures. Examines how new forms of communication exert social, political, and cultural influences in the global context. Explores how technological innovation and accelerating media affect social values and behaviors in the popular and global adoption of a media device. Includes two papers and a research project on aspects of media history. Students taking graduate version complete additional assignments. Enrollment limited.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq72_0`, {timeout:5});
COURSE_MODULE.evaluate_req("72_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("72_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
