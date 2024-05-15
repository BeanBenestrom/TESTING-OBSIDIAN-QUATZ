catalog: [degree_requirements](https://eecsis.mit.edu/degree_requirements.html#PROB)

<font style="color: grey">Probability grounding</font>

<span class="sus-course">[[🎓Universities/MIT/18.05 Introduction to Probability and Statistics | 18.05 Introduction to Probability and Statistics]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.600 Probability and Random Variables | 18.600 Probability and Random Variables]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.062J Mathematics for Computer Science | 18.062J Mathematics for Computer Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3700 Introduction to Probability | 6.3700 Introduction to Probability]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3800 Introduction to Inference | 6.3800 Introduction to Inference]]</span>

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