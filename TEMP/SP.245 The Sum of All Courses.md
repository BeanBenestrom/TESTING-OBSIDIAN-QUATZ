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

catalog [SP.245](http://student.mit.edu/catalog/mSPa.html#SP.245)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4213_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4213_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4213_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4213_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Provides an overview of the wide variety of majors and joint majors as well as minors and concentrations at MIT. At each lecture, faculty from two to three departments describe their fields. One-hour seminars and panels are given on informative and engaging topics such as, "The Rationale Behind the MIT Curriculum," "The Purpose of an Education," "Integrating by Parts and Other Life Hacks," "Etiquette and Why it Is Important," "So, Darwin, Shakespeare, and Newton Walk into a Bar," "How to Avoid Burnout," "What is your Implicit Bias?," "How to be a Good Human," "Social Impact, Unintended Consequences, and Moral Hazards," and include panel discussions with MIT Administration and MIT's Distinguished Professors. Subject can count toward the 6-unit discovery-focused credit limit for first year students. Limited to 1132; preference to first-year students.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4213_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4213_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4213_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
