---
tags:
  - course
ctime: 2024-04-18T00:19:29
mstime: 2024-04-18T00:19:29
level: undergraduate
subject: 
university: mit
completion: open
percentage: 0
prereq: None.
coreq: None.
---

catalog [SP.257](http://student.mit.edu/catalog/mSPa.html#SP.257)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4225_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4225_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4225_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4225_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Provides students with an opportunity to network and think strategically about their global careers in the energy sector. Content is international, drawing from MISTI's global network of companies and institutions, and professionals, with attention to energy research and skills necessary to work in the energy field. Through weekly discussion-based sessions, students learn from numerous sources: MISTI hosts, MITEI, alumni, and more. As a First-Year Discovery subject, focuses on career goals and skills, providing both a global and local perspective on energy topics. Open to students of all levels and disciplines, students can learn from each other and consider personal and professional goals in a multidisciplinary and international capacity. This subject can count toward the 6-unit discovery-focused credit limit for first-year students.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4225_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4225_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4225_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
