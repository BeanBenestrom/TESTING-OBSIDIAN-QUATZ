---
tags:
  - course
ctime: 2024-04-18T00:19:28
mstime: 2024-04-18T00:19:28
level: undergraduate
subject: 
university: mit
completion: open
percentage: 0
prereq: None.
coreq: None.
---

catalog [CMS.314[J]](http://student.mit.edu/catalog/mCMSa.html#CMS.314), [21W.753[J]](http://student.mit.edu/catalog/m21Wb.html#21W.753), [CMS.814](http://student.mit.edu/catalog/mCMSa.html#CMS.814)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq47_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq47_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq47_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq47_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Engages students in theory and practice of using computational techniques for developing expressive digital media works. Surveys approaches to understanding human imaginative processes, such as constructing concepts, metaphors, and narratives, and applies them to producing and understanding socially, culturally, and critically meaningful works in digital media. Readings engage a variety of theoretical perspectives from cognitive linguistics, literary and cultural theory, semiotics, digital media arts, and computer science. Students produce interactive narratives, games, and related forms of software art. Some programming and/or interactive web scripting experience (e.g., Flash, Javascript) is desirable. Students taking the graduate version complete a project requiring more in-depth theoretical engagement.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq47_0`, {timeout:5});
COURSE_MODULE.evaluate_req("47_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("47_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
