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

catalog [NS.12](http://student.mit.edu/catalog/mNSa.html#NS.12)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4141_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4141_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4141_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4141_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">A study of the US Navy and the influence of sea power upon history. Incorporates both a historical and political science process to explore the major events, attitudes, personalities, and circumstances which have imbued the US Navy with its proud history and rich tradition. Deals with issues of national imperatives in peacetime as well as war, varying maritime philosophies which were interpreted into naval strategies/doctrines, budgetary concerns which shaped force realities, and the pursuit of American diplomatic objectives, concluding with the current search for direction in the post-Cold War era and beyond.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4141_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4141_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4141_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
