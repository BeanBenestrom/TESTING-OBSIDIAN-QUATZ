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

catalog [CMS.590[J]](http://student.mit.edu/catalog/mCMSa.html#CMS.590), [11.127[J]](http://student.mit.edu/catalog/m11a.html#11.127), [11.252[J]](http://student.mit.edu/catalog/m11b.html#11.252), [CMS.863[J]](http://student.mit.edu/catalog/mCMSa.html#CMS.863)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq78_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq78_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq78_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq78_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Immerses students in the process of building and testing their own digital and board games in order to better understand how we learn from games. Explores the design and use of games in the classroom in addition to research and development issues associated with computer-based (desktop and handheld) and non-computer-based media. In developing their own games, students examine what and how people learn from them (including field testing of products), as well as how games can be implemented in educational settings. All levels of computer experience welcome. Students taking graduate version complete additional assignments.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq78_0`, {timeout:5});
COURSE_MODULE.evaluate_req("78_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("78_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
