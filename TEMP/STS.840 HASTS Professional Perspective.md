---
tags:
  - course
ctime: 2024-04-18T00:19:29
mstime: 2024-04-18T00:19:29
level: graduate
subject: 
university: mit
completion: open
percentage: 0
prereq: Permission of advisor
coreq: None.
---

catalog [STS.840](http://student.mit.edu/catalog/mSTSb.html#STS.840)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4171_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4171_0">Permission of advisor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4171_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4171_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Required for doctoral students in the doctoral program in History, Anthropology, and Science, Technology and Society (HASTS) to explore and gain professional perspective through academic, non-profit, government, or industry experiences. Professional perspective options include, but are not limited to, internships, teacher training, professional development for entry into academia, or public academic engagement. For an internship experience, an offer from a company or organization is required prior to enrollment. A written narrative or report is required upon completion of the experience. Proposals subject to departmental approval in consultation with advisor.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4171_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4171_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4171_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
