---
tags: [course]
ctime: "2024-04-18T00:19:28"
mstime: "2024-04-18T00:19:28"

level: undergraduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/CMS.100 Introduction to Media Studies> or permission of instructor"
coreq: "None."
---

catalog [CMS.338](http://student.mit.edu/catalog/mCMSa.html#CMS.338), [CMS.838](http://student.mit.edu/catalog/mCMSa.html#CMS.838)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq52_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq52_0">[[🎓Universities/MIT/CMS.100 Introduction to Media Studies | CMS.100]] or permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq52_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq52_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Discusses emerging technologies and techniques available to media-makers (e.g., location-based technologies, transmedia storytelling, crowdsourcing, and interactivity) and their implications on the film and television documentary. Studies the development of these tools and considers the many new directions in which they may take the genre. Includes screenings, meetings with documentary makers, and an experimental component in which students can explore new approaches to documentary production. Students taking graduate version complete additional assignments.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq52_0`, {timeout:5});
COURSE_MODULE.evaluate_req("52_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("52_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
