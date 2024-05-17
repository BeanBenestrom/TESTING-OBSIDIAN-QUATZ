---
tags:
  - course
ctime: 2024-04-18T00:19:28
mstime: 2024-04-18T00:19:28
level: graduate
subject: 
university: mit
completion: open
percentage: 0
prereq: One subject in Comparative Media Studies or permission of instructor
coreq: None.
---

catalog [CMS.864](http://student.mit.edu/catalog/mCMSa.html#CMS.864)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq123_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq123_0">One subject in Comparative Media Studies or permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq123_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq123_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Practical instruction in the design and analysis of non-digital games. Provides students the texts, tools, references, and historical context to analyze and compare game designs across a variety of genres. In teams, students design, develop, and thoroughly test their original games to better understand the interaction and evolution of game rules. Covers various genres and types of games, including sports, game shows, games of chance, card games, schoolyard games, board games, and role-playing games. Students taking the graduate version complete additional assignments. Limited to 20.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq123_0`, {timeout:5});
COURSE_MODULE.evaluate_req("123_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("123_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
