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
coreq: <🎓Universities/MIT/CMS.586J Introduction to Education, Looking Forward and Looking Back on Education>
---

catalog [CMS.591[J]](http://student.mit.edu/catalog/mCMSa.html#CMS.591), [11.129[J]](http://student.mit.edu/catalog/m11a.html#11.129)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq79_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq79_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq79_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq79_0">[[🎓Universities/MIT/CMS.586J Introduction to Education, Looking Forward and Looking Back on Education | CMS.586]]</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Concentrates on core set of skills and knowledge necessary for teaching in secondary schools. Topics include classroom management, student behavior and motivation, curriculum design, educational reform, and the teaching profession. Classroom observation is a key component. Assignments include readings from educational literature, written reflections on classroom observations, practice teaching and constructing curriculum. The first of the three-course sequence necessary to complete the Teacher Education Program. Limited to 15; preference to juniors and seniors.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq79_0`, {timeout:5});
COURSE_MODULE.evaluate_req("79_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("79_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
