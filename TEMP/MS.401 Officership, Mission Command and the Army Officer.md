---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: undergraduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/MS.302 Applied Leadership in Small Unit Operations>"
coreq: "None."
---

catalog [MS.401](http://student.mit.edu/catalog/mMSa.html#MS.401)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4137_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4137_0">[[🎓Universities/MIT/MS.302 Applied Leadership in Small Unit Operations | MS.302]]</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4137_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4137_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Develops proficiency in planning and executing complex operations, functioning as a member of an organizational staff, assessing risk, making ethical decisions, and leading fellow students. Through assignment to leadership positions in the ROTC Battalion, students plan and lead the execution of labs, directing and controlling the corps of cadets, enhancing their oral and written communications, and improving their application of troop-leading procedures and problem solving.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4137_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4137_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4137_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
