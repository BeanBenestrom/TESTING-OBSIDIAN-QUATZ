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

catalog [EC.075](http://student.mit.edu/catalog/mECa.html#EC.075)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3859_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3859_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3859_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3859_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Seminar participants define and study the development stages of new enterprises at MIT, from the exciting moment a new idea for a tech product or service is realized, through to selling, customer support, and the next new idea. Follows the history of successful MIT spin-off companies with attention to the people (and their ideas) behind the start-up. Students attend MIT technology and science start-up case presentations given by individuals and teams working from zero-stage, and by partners in going concerns of historical relevance to the Institute and the economy.  Second in a two-part series (seminars do not have to be taken sequentially; see EC.074 in fall term).</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3859_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3859_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3859_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
