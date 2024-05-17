---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: graduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/18.02 Calculus>"
coreq: "None."
---

catalog [HST.191](http://student.mit.edu/catalog/mHSTa.html#HST.191)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3999_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3999_0">[[🎓Universities/MIT/18.02 Calculus | Calculus II (GIR)]]</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3999_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3999_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Provides training on how to comprehend, critique and communicate findings from biomedical literature. Considers how to assess the importance of chance in the interpretation of experimental data. Topics include probability theory, chi-squared and t-tests, ANOVA, linear and logistic regression, survival analysis, and statistical analysis using MATLAB. Includes critical reading of studies published in medical literature.  Enrollment limited; restricted to HST students.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3999_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3999_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3999_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
