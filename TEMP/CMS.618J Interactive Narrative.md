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

catalog [CMS.618[J]](http://student.mit.edu/catalog/mCMSa.html#CMS.618), [21L.489[J]](http://student.mit.edu/catalog/m21La.html#21L.489), [21W.765[J]](http://student.mit.edu/catalog/m21Wb.html#21W.765), [CMS.845](http://student.mit.edu/catalog/mCMSa.html#CMS.845)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq93_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq93_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq93_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq93_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Provides a workshop environment for understanding interactive narrative (print and digital) through critical writing, narrative theory, and creative practice. Covers important multisequential books, hypertexts, and interactive fictions. Students write critically, and give presentations, about specific works; write a short multisequential fiction; and develop a digital narrative system, which involves significant writing and either programming or the structuring of text. Programming ability helpful.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq93_0`, {timeout:5});
COURSE_MODULE.evaluate_req("93_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("93_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
