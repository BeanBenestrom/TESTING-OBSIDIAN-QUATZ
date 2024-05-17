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

catalog [CMS.359[J]](http://student.mit.edu/catalog/mCMSa.html#CMS.359), [21G.042[J]](http://student.mit.edu/catalog/m21Ga.html#21G.042), [21H.352[J]](http://student.mit.edu/catalog/m21Hb.html#21H.352), [21L.492[J]](http://student.mit.edu/catalog/m21La.html#21L.492), [21G.133](http://student.mit.edu/catalog/m21Gb.html#21G.133)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq66_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq66_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq66_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq66_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Analyzing core chapters of the great Chinese epic novel, Three Kingdoms, and its adaptations across diverse media, considers what underlies the appeal of this classic narrative over the centuries. Through focus on historical events in the period 206 BC to AD 280, examines the representation of power, diplomacy, war, and strategy, and explores the tension among competing models of political authority and legitimacy. Covers basic elements of classical Chinese political and philosophical thought, and literary and cultural history. Final group project involves digital humanities tools. Readings in translation. Films and video in Chinese with English subtitles.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq66_0`, {timeout:5});
COURSE_MODULE.evaluate_req("66_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("66_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
