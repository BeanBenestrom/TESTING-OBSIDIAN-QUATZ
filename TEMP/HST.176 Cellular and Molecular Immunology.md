---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: graduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/7.05 General Biochemistry>"
coreq: "None."
---

catalog [HST.176](http://student.mit.edu/catalog/mHSTa.html#HST.176)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3998_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3998_0">[[🎓Universities/MIT/7.05 General Biochemistry | 7.05]]</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3998_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3998_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Covers cells and tissues of the immune system, lymphocyte development, the structure and function of antigen receptors, the cell biology of antigen processing and presentation including molecular structure and assembly of MHC molecules, lymphocyte activation, the biology of cytokines, leukocyte-endothelial interactions, and the pathogenesis of immunologically mediated diseases. Consists of lectures and tutorials in which clinical cases are discussed with faculty tutors. Details of each case covering a number of immunological issues in the context of disease are posted on a student website. Only HST students may register under HST.175, graded P/D/F. Limited to 45.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3998_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3998_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3998_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
