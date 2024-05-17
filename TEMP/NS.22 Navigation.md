---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: undergraduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/NS.11 Introduction to Naval Science> or permission of instructor"
coreq: "None."
---

catalog [NS.22](http://student.mit.edu/catalog/mNSa.html#NS.22)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4143_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4143_0">[[🎓Universities/MIT/NS.11 Introduction to Naval Science | NS.11]] or permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4143_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4143_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Comprehensive study of the theory, principles, and procedures of piloting and maritime navigation, including mathematics of navigation, practical work involving navigational instruments, sight reduction by &lt;em&gt;pro forma&lt;/em&gt; and computerized methods, charts, publications, and voyage planning. CORTRAMID cruise recommended.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4143_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4143_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4143_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
