---
tags: [course]
ctime: "2024-04-18T00:19:28"
mstime: "2024-04-18T00:19:28"

level: undergraduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/6.100A Introduction to Computer Science Programming in Python> or <🎓Universities/MIT/CMS.301 Game Design Methods>"
coreq: "None."
---

catalog [CMS.611[J]](http://student.mit.edu/catalog/mCMSa.html#CMS.611), [6.4570[J]](http://student.mit.edu/catalog/m6d.html#6.4570)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq89_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq89_0">[[🎓Universities/MIT/6.100A Introduction to Computer Science Programming in Python | 6.100A]] or [[🎓Universities/MIT/CMS.301 Game Design Methods | CMS.301]]</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq89_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq89_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Introduces students to the complexities of working in small, multidisciplinary teams to develop video games. Covers creative design and production methods, stressing design iteration and regular testing across all aspects of game development (design, visual arts, music, fiction, and programming). Assumes a familiarity with current video games, and the ability to discuss games critically. Previous experience in audio design, visual arts, or project management recommended. Limited to 36.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq89_0`, {timeout:5});
COURSE_MODULE.evaluate_req("89_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("89_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
