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

catalog [EC.751](http://student.mit.edu/catalog/mECa.html#EC.751), [EC.793](http://student.mit.edu/catalog/mECa.html#EC.793)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3873_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3873_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3873_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3873_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Students explore possible uses of repurposed electronic devices in several sectors of development, including agriculture, education, health, and energy, to have a positive impact on people living in low-income communities. Guest lecturers provide insight into current trends in information and communication technology for development. Students work in teams to apply principles of participatory and inclusive design to specific projects that they develop in collaboration with community innovators in refugee camps in Northern Uganda and rural areas of Tanzania. Optional travel to Uganda and Tanzania occurs over subsequent IAP with D-Lab partners in the field. Graduate students complete additional assignments.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3873_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3873_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3873_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
