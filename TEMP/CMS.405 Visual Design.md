---
tags: [course]
ctime: "2024-04-18T00:19:28"
mstime: "2024-04-18T00:19:28"

level: undergraduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/21L.011 Introduction to Film Studies> or <🎓Universities/MIT/CMS.100 Introduction to Media Studies>"
coreq: "None."
---

catalog [CMS.405](http://student.mit.edu/catalog/mCMSa.html#CMS.405)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq74_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq74_0">[[🎓Universities/MIT/21L.011 Introduction to Film Studies | 21L.011]] or [[🎓Universities/MIT/CMS.100 Introduction to Media Studies | CMS.100]]</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq74_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq74_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Examines the process of making and sharing visual artifacts using a trans-cultural, trans-historical, constructionist approach. Explores the relationship between perceived reality and the narrative imagination, how an author's choice of medium and method constrains the work, how desire is integrated into the structure of a work, and how the cultural/economic opportunity for exhibition/distribution affects the realization of a work. Instruction and practice in written and oral communication provided. Limited to 20.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq74_0`, {timeout:5});
COURSE_MODULE.evaluate_req("74_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("74_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
