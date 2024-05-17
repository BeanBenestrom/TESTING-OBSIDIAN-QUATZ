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
coreq: "<🎓Universities/MIT/AS.101 Heritage and Values of the United States Air Force>"
---

catalog [AS.111](http://student.mit.edu/catalog/mASa.html#AS.111)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq2_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq2_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq2_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq2_0">[[🎓Universities/MIT/AS.101 Heritage and Values of the United States Air Force | AS.101]]</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">First-year General Military Course. Includes a study of Air Force customs and courtesies, drill and ceremonies, and military commands. Also includes studying the environment of an Air Force officer and learning about areas of opportunity available to commissioned officers, as well as interviews, guidance, and information to increase the understanding, motivation, and performance of other cadets.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq2_0`, {timeout:5});
COURSE_MODULE.evaluate_req("2_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("2_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
