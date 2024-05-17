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
coreq: "<🎓Universities/MIT/MS.101 Introduction to the Army and Critical Thinking>"
---

catalog [MS.102](http://student.mit.edu/catalog/mMSa.html#MS.102)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4131_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4131_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4131_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4131_0">[[🎓Universities/MIT/MS.101 Introduction to the Army and Critical Thinking | MS.101]]</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Introduces students to the professional challenges and competencies that are needed for effective execution of the profession of arms and Army communication. Explores how Army ethics and values shape the Army and the specific ways they are inculcated into Army culture. Investigates the Army leadership dimensions, attributes, and core competencies and gain practical experience using critical communication skills.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4131_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4131_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4131_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
