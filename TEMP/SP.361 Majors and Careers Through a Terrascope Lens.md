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

catalog [SP.361](http://student.mit.edu/catalog/mSPa.html#SP.361)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4231_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4231_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4231_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4231_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">MIT alumni pursuing sustainability-oriented careers describe ways in which their major and career choices have provided them with the lenses through which they see the problems they work to solve. Students participate in guided reflection, focused on making the discussion relevant to their own personal situations and affinities. Students strengthen their ability to think deeply about their goals, for MIT and for the world beyond, and come into direct contact with alumni who can continue to mentor them through this process. Open to all undergraduates, regardless of Terrascope affiliation.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4231_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4231_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4231_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
