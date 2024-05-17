---
tags: [course]
ctime: "2024-04-18T00:19:28"
mstime: "2024-04-18T00:19:28"

level: undergraduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/AS.101 Heritage and Values of the United States Air Force> or permission of instructor"
coreq: "<🎓Universities/MIT/AS.112 Leadership Laboratory>"
---

catalog [AS.102](http://student.mit.edu/catalog/mASa.html#AS.102)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq1_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq1_0">[[🎓Universities/MIT/AS.101 Heritage and Values of the United States Air Force | AS.101]] or permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq1_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq1_0">[[🎓Universities/MIT/AS.112 Leadership Laboratory | AS.112]]</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Survey course designed to introduce students to the United States Air Force. Provides an overview of the basic characteristics, missions, and organizations of the Air Force. AS.102 is a continuation of AS.101.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq1_0`, {timeout:5});
COURSE_MODULE.evaluate_req("1_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("1_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
