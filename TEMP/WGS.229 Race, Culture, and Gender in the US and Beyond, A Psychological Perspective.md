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

catalog [WGS.229](http://student.mit.edu/catalog/mWGSa.html#WGS.229)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4282_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4282_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4282_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4282_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Examines the biopsychosocial factors which impact racial-ethnic identity, racial and cultural socialization, and experiences of prejudice, bias, discrimination, and racial microaggressions across gender identities. Reviews topics in multicultural psychology from the lens of challenging ethnocentric biases in the field. Critically evaluates the intersection of race with other social identities (e.g., gender, sexual identity, and socioeconomic status) and how it impacts human behavior. Using a case study approach, students integrate empirical evidence from international psychosocial research on oppression in order to provide more breadth in understanding the influence of race and gender upon human behavior. Develops multicultural competency skills essential for practice in clinical and non-clinical organizational settings. Limited to 25.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4282_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4282_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4282_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
