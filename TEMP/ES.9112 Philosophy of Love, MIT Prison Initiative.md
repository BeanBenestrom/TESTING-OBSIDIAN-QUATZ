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

catalog [ES.9112](http://student.mit.edu/catalog/mESa.html#ES.9112)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3933_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3933_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3933_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3933_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Explores the nature of love through works of philosophy, literature, film, poetry, and individual experience. Investigates the distinction among eros (desiring or appreciative love), philia (mutuality), and agape (love as pure giving). Students discuss ideas of love as a feeling, an action, a species of 'knowing someone,' or a way to give or take. Authors include Plato, Kant, Buber, D. H. Lawrence, Rumi, and Aristotle. Taught inside a secure Massachusetts correctional facility with a mix of MIT students and incarcerated students. Limited to 10.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3933_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3933_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3933_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
