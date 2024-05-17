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

catalog [SP.254](http://student.mit.edu/catalog/mSPa.html#SP.254)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4222_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4222_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4222_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4222_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">One of the major challenges of our time is to provide more energy to a growing world population while simultaneously reducing carbon emissions to combat climate change. Climate science shows that it is urgent to accomplish this soon, as the residence times of most greenhouse gasses are large. Subject offers exposure to relevant research that is being done in this context at MIT. Students review short papers on low carbon technologies and climate change; hear from faculty, researchers, and industry representatives associated with the MITEI Low Carbon Energy Centers; and create a digital story exploring the connections between the challenges, research, and current deployment of technologies. Offers context to students' future academic work and exposes students to ways in which many MIT majors apply to energy. Subject can count toward the 6-unit discovery-focused credit limit for first-year students.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4222_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4222_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4222_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
