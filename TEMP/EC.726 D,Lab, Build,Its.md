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

catalog [EC.726](http://student.mit.edu/catalog/mECa.html#EC.726), [EC.796](http://student.mit.edu/catalog/mECa.html#EC.796)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3869_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3869_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3869_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3869_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Engages students in the creation of "build-its," hands-on pedagogical tools developed by D-Lab to teach workshop and design skills to a diverse audience around the world. Studies principles of experiential learning and successful examples of teaching in makerspaces and innovation centers. Students develop their own build-it, test and evaluate it with local students, and create instructions for its use. Optional travel opportunities exist over the summer to test the build-it at a D-Lab summit or training abroad. Opportunities for funded travel available. Students taking graduate version complete additional assignments. Opportunities for funded travel available. Limited to 16.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3869_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3869_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3869_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
