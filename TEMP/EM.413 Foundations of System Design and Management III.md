---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: graduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/EM.412 Foundations of System Design and Management II>"
coreq: "None."
---

catalog [EM.413](http://student.mit.edu/catalog/mEMa.html#EM.413)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3902_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3902_0">[[🎓Universities/MIT/EM.412 Foundations of System Design and Management II | EM.412]]</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3902_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3902_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Presents advanced concepts in systems architecture, systems engineering and project management in an integrated manner through lectures, recitations, opportunity sets, guest lectures, and a semester-long team project. Topics emphasize complexity management, systems integration, verification, validation, and lifecycle management. Specific lifecycle properties addressed include quality, safety, robustness, resilience, flexibility and evolvability of systems over time. Additional topics include monitoring and control, the rework cycle, managing portfolios and programs of projects in a multi-cultural and global context, and managing product families and platforms. Restricted to students in the SDM program.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3902_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3902_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3902_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
