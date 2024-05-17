---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: graduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/EM.411 Foundations of System Design and Management>"
coreq: "None."
---

catalog [EM.412](http://student.mit.edu/catalog/mEMa.html#EM.412)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3901_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3901_0">[[🎓Universities/MIT/EM.411 Foundations of System Design and Management | EM.411]]</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3901_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3901_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Deepens the foundations of systems architecture, systems engineering and project management introduced in EM.411 though a synchronized combination of lectures, recitations, opportunity sets, guest speakers, and team projects. Topics emphasize the transition from early conceptual design to detailed design and system integration. Features a technology showcase and project forum where students, faculty and company sponsors meet to discuss and select projects for EM.413. Includes team-based exercises and design challenges. Restricted to students in the SDM program.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3901_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3901_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3901_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
