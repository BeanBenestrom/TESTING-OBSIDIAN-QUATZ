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

catalog [CMS.311[J]](http://student.mit.edu/catalog/mCMSa.html#CMS.311), [21G.055[J]](http://student.mit.edu/catalog/m21Ga.html#21G.055)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq45_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq45_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq45_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq45_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Debates over national and media identity in Weimar and Nazi Germany. Production and use of media under extreme political and social conditions with a focus on films (such as Nosferatu, Berlin, M, and Triumph des Willens) and other media. Media approached as both texts and systems. Considers the legacy of the period, in terms of stylistic influence (e.g. film noir), techniques of persuasion, and media's relationship to social and economic conditions. Taught in English. Enrollment limited.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq45_0`, {timeout:5});
COURSE_MODULE.evaluate_req("45_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("45_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
