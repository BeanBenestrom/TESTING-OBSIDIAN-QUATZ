---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: graduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/EM.441 Integrated Design Lab I> or permission of instructor"
coreq: "None."
---

catalog [EM.442](http://student.mit.edu/catalog/mEMa.html#EM.442)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3909_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3909_0">[[🎓Universities/MIT/EM.441 Integrated Design Lab I | EM.441]] or permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3909_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3909_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Presents advanced topics in integrated design and product development. Students pursue a product development project as a case study for understanding how teams work together to define and test a new product. Provides exposure to the state-of-the-art in product definition, product architectures, market testing, competitive analysis, product planning strategy, business case construction, and life cycle design. Students apply their previously acquired product development knowledge and engage in ongoing reflection in an action-oriented setting. Restricted to Integrated Design and Management (IDM) students.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3909_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3909_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3909_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
