---
tags: [course]
ctime: "2024-04-18T00:19:29"
mstime: "2024-04-18T00:19:29"

level: graduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "( <🎓Universities/MIT/6.7900 Machine Learning> and <🎓Universities/MIT/6.7930J Machine Learning for Healthcare> ) or permission of instructor"
coreq: "None."
---

catalog [HST.953](http://student.mit.edu/catalog/mHSTb.html#HST.953)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4021_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4021_0">( [[🎓Universities/MIT/6.7900 Machine Learning | 6.7900]] and [[🎓Universities/MIT/6.7930J Machine Learning for Healthcare | 6.7930]] ) or permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4021_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4021_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Examines the practical considerations for operationalizing machine learning in healthcare settings, with a focus on robust, private, and fair modeling using real retrospective healthcare data. Explores the pre-modeling creation of dataset pipeline to the post-modeling "implementation science," which addresses how models are incorporated at the point of care. Students complete three homework assignments (one each in machine learning, visualization, and implementation), followed by a project proposal and presentation. Students gain experience in dataset creation and curation, machine learning training, visualization, and deployment considerations that target utility and clinical value. Students partner with computer scientists, engineers, social scientists, and clinicians to better appreciate the multidisciplinary nature of data science.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4021_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4021_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4021_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
