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
prereq: Permission of instructor
coreq: None.
---

catalog [CMS.848](http://student.mit.edu/catalog/mCMSa.html#CMS.848), [21W.748](http://student.mit.edu/catalog/m21Wa.html#21W.748)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq122_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq122_0">Permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq122_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq122_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Focuses on the critical making of apocalyptic, post-apocalyptic and dystopian stories across various narrative media. Considers the long history of Western apocalypticism as well as the uses and abuses of apocalypticism across time. Examines a wide variety of influential texts in order to enhance students' creative and theoretical repertoires. Students create their own apocalyptic stories and present on selected texts. Investigates conventions such as plague, zombies, nuclear destruction, robot uprising, alien invasion, environmental collapse, and supernatural calamities. Considers questions of race, gender, sexuality, colonialism, trauma, memory, witness, and genocide. Intended for students with prior creative writing experience. Students taking graduate version complete additional assignments. Limited to 15.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq122_0`, {timeout:5});
COURSE_MODULE.evaluate_req("122_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("122_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
