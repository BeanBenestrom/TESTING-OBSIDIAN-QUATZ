---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: undergraduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/NS.21 Leadership and Management>"
coreq: "None."
---

catalog [NS.42](http://student.mit.edu/catalog/mNSa.html#NS.42)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4148_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4148_0">[[🎓Universities/MIT/NS.21 Leadership and Management | NS.21]]</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4148_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4148_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Analyzes ethical decision-making and leadership principles. Students read and discuss texts written by such philosophers as Aristotle, Kant, and Mill to gain familiarity with the realm of ethical theory. Students then move on to case studies in which they apply these theories to resolve moral dilemmas. Provides a basic background in the duties and responsibilities of a junior division and watch officer; strong emphasis on the junior officer's responsibilities in training, counseling, and career development. Student familiarization with equal opportunity and drug/alcohol rehabilitation programs. Principles of leadership reinforced through leadership case studies.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4148_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4148_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4148_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
