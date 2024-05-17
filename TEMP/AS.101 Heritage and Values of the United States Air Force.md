---
tags: [course]
ctime: "2024-04-18T00:19:28"
mstime: "2024-04-18T00:19:28"

level: undergraduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "None."
coreq: "<🎓Universities/MIT/AS.111 Leadership Laboratory>"
---

catalog [AS.101](http://student.mit.edu/catalog/mASa.html#AS.101)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq0_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq0_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq0_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq0_0">[[🎓Universities/MIT/AS.111 Leadership Laboratory | AS.111]]</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Survey course designed to introduce students to the United States Air Force. Provides an overview of the basic characteristics, missions, and organizations of the Air Force.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq0_0`, {timeout:5});
COURSE_MODULE.evaluate_req("0_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("0_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
