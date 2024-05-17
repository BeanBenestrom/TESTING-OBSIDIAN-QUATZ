---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: graduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/MAS.809 Decoders 1.9, Introduction to Microfabrication> and permission of instructor"
coreq: "None."
---

catalog [MAS.810](http://student.mit.edu/catalog/mMASa.html#MAS.810)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4098_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4098_0">[[🎓Universities/MIT/MAS.809 Decoders 1.9, Introduction to Microfabrication | MAS.809]] and permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4098_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4098_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Builds on the combination of knowledge and skills learned in D1.0 and D1.7, respectively to guide students to develop their own mechanically adaptive (i.e., stretchable &amp; flexible) piezoelectric systems. Students write an article about their research findings that will be published on the course website by the end of term. Instructs how to do literature review, to compose clear and concise sentences to describe findings, and to write a perspective article in a collective manner. Limited to 10; no listeners.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4098_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4098_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4098_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
