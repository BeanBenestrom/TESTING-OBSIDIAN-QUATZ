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
prereq: Permission of instructor
coreq: None.
---

catalog [MAS.712](http://student.mit.edu/catalog/mMASa.html#MAS.712)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4091_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4091_0">Permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4091_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4091_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">An introduction to the design of technologies, activities, and communities to support young people in creative learning experiences. Through readings, activities, and group discussions, explores the four P's of creative learning: projects, passion, peers, and play. Draws on examples from the Lifelong Kindergarten group at the MIT Media Lab, including the Scratch programming language and online community. Special focus on how to engage learners from many different backgrounds, with many different interests.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4091_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4091_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4091_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
