catalog: [degree_requirements](https://eecsis.mit.edu/degree_requirements.html#EECS12)

<font style="color: grey">EECS subjects at levels 1 and 2</font>

<span class="sus-course">[[🎓Universities/MIT/6.1910 Computation Structures | 6.1910 Computation Structures]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3800 Introduction to Inference | 6.3800 Introduction to Inference]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3900 Introduction to Machine Learning | 6.3900 Introduction to Machine Learning]]</span>

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
const courses = await UTILITY_MODULE.waitForElements(`.sus-course a`, {timeout:5});
courses.forEach( course => { COURSE_MODULE.link_completion(tp, course, true); });
// --------------------------------
}; main();
```