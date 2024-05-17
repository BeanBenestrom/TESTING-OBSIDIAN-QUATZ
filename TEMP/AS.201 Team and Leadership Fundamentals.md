---
tags: [course]
ctime: "2024-04-18T00:19:28"
mstime: "2024-04-18T00:19:28"

level: undergraduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/AS.102 Heritage and Values of the United States Air Force> or permission of instructor"
coreq: "<🎓Universities/MIT/AS.211 Leadership Laboratory>"
---

catalog [AS.201](http://student.mit.edu/catalog/mASa.html#AS.201)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4_0">[[🎓Universities/MIT/AS.102 Heritage and Values of the United States Air Force | AS.102]] or permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4_0">[[🎓Universities/MIT/AS.211 Leadership Laboratory | AS.211]]</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Focuses on laying the foundation for teams and leadership. Topics center on skills that allow cadets to improve their leadership on a personal level and within a team. Prepares cadets for their field training experience where they have the opportunity to put the concepts covered in to practice. Aims to instill a leadership mindset and motivate sophomore students to transition from AFROTC cadet to AFROTC officer candidate.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
