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

catalog [CC.111[J]](http://student.mit.edu/catalog/mCCa.html#CC.111), [17.04[J]](http://student.mit.edu/catalog/m17a.html#17.04)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq152_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq152_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq152_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq152_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Students read early modern political theorists, and trace the growth of the value of freedom.  Examines the modern definition of freedom, and the obligations that people accept in honoring it.  Also investigates how these obligations are captured in the principles of our political association.  Studies how the centrality of freedom plays out in the political thought of such authors as Hobbes, Locke, Rousseau, Burke and Montesquieu.  Students also debate which notions of freedom inspire and sustain the American experiment by carefully reading the documents and arguments of the founding of the United States. Preference to students in Concourse.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq152_0`, {timeout:5});
COURSE_MODULE.evaluate_req("152_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("152_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
