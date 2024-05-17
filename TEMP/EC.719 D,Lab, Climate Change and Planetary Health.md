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

catalog [EC.719](http://student.mit.edu/catalog/mECa.html#EC.719), [EC.789](http://student.mit.edu/catalog/mECa.html#EC.789)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3866_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3866_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3866_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3866_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Examines the current state and future projections of climate change and its effects on human, ecosystem, and planetary health, and develops solutions for these challenges. Class is project-based, student-focused, experiential, and transdisciplinary. Emphasizes nature- and community-based solutions, both local and global, with a focus on environmental and climate justice. Participation and teamwork are fundamental, as are experiential activities such as field trips to zero-carbon buildings and to sites undergoing rapid transformation. Working individually or in teams, students develop a term project on a climate change or planetary health solution of their choice, applying knowledge and skills to craft innovative, sustainable real-world solutions. Students taking graduate version complete additional assignments.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3866_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3866_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3866_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
