---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: undergraduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/MS.401 Officership, Mission Command and the Army Officer>"
coreq: "None."
---

catalog [MS.402](http://student.mit.edu/catalog/mMSa.html#MS.402)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4138_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4138_0">[[🎓Universities/MIT/MS.401 Officership, Mission Command and the Army Officer | MS.401]]</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4138_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4138_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Examines the US National Security Structure and how the Army operates as part of the joint force in a whole of government approach. Studies how various operational variables affect military operations. Through assignment to leadership positions, students actively plan and execute training within the program, direct and control an organization, enhance oral and written communications, and apply troop-leading procedures. Students also examine past leaders through a staff ride to the battlefields of Lexington and Concord.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4138_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4138_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4138_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
