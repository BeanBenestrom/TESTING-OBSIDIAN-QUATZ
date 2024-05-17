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

catalog [ES.9114](http://student.mit.edu/catalog/mESa.html#ES.9114)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3934_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3934_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3934_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3934_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Addresses the philosophical question of what a non-violent life entails. Investigates its ethical dimensions and challenges, and considers whether we can derive a comprehensive moral theory from the principle of non-violence. Discusses the issues of lying, the duty to forgive, non-violent communication, the ethics of our relationship to anger, the possibility of loving enemies, and the ethics of punishment and rehabilitation.  Includes readings from primary exponents of non-violence, such as Tolstoy, Gandhi and King. Taught inside a secure Massachusetts correctional facility with a mix of MIT students and incarcerated students. Limited to 10.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3934_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3934_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3934_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
