---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: undergraduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/MS.102 Introduction to the Profession of Arms> or permission of instructor"
coreq: "None."
---

catalog [MS.201](http://student.mit.edu/catalog/mMSa.html#MS.201)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4133_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4133_0">[[🎓Universities/MIT/MS.102 Introduction to the Profession of Arms | MS.102]] or permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4133_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4133_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Familiarizes students with the professional practice of ethics within the Army by exploring Army values and ethics along with the fundamentals of leadership, personal development, and tactics at the small unit level. Explores ethical and tactical decision-making case studies. Students required to demonstrate writing skills and present information briefings as preparation for development in becoming successful future officers.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4133_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4133_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4133_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
