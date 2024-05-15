catalog: [degree_requirements](https://eecsis.mit.edu/degree_requirements.html#Computation-centric)

<font style="color: grey">6-4 Computation-centric subjects</font>

<span class="sus-course">[[🎓Universities/MIT/18.410J Design and Analysis of Algorithms | 18.410J Design and Analysis of Algorithms]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4400 Computer Graphics | 6.4400 Computer Graphics]]</span>
<span class="sus-course">[[🎓Universities/MIT/15.093J Optimization Methods | 15.093J Optimization Methods]]</span>

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