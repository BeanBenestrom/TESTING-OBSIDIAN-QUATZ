---
tags: [course]
ctime: "2024-04-18T00:19:28"
mstime: "2024-04-18T00:19:28"

level: undergraduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/CMS.592J Educational Theory and Practice II>"
coreq: "None."
---

catalog [CMS.593[J]](http://student.mit.edu/catalog/mCMSa.html#CMS.593), [11.131[J]](http://student.mit.edu/catalog/m11a.html#11.131)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq81_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq81_0">[[🎓Universities/MIT/CMS.592J Educational Theory and Practice II | CMS.592]]</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq81_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq81_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Students continue their IAP student teaching through mid March. Topics include educational psychology, theories of learning, and using technology and evaluating its effectiveness to enhance student learning. Assignments include readings from educational literature, written reflections on student teaching, presentations on class topics and creating a project that supports student learning at the school where the MIT student is teaching. This is the third of the three-course sequence necessary to complete the Teacher Education Program.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq81_0`, {timeout:5});
COURSE_MODULE.evaluate_req("81_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("81_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
