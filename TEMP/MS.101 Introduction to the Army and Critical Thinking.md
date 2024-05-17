---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: undergraduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "None."
coreq: "<🎓Universities/MIT/MS.102 Introduction to the Profession of Arms>"
---

catalog [MS.101](http://student.mit.edu/catalog/mMSa.html#MS.101)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4130_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4130_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4130_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4130_0">[[🎓Universities/MIT/MS.102 Introduction to the Profession of Arms | MS.102]]</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Introduces students to the personal challenges and competencies that are critical for effective leadership and communication. Explores how the personal development of cultural understanding, goal setting, time management, stress management and comprehensive fitness relate to leadership, officership, and the Army profession.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4130_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4130_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4130_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
