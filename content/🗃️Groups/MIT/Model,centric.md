catalog: [degree_requirements](https://eecsis.mit.edu/degree_requirements.html#Model-centric)

<font style="color: grey">6-4 Model-centric subjects</font>

<span class="sus-course">[[🎓Universities/MIT/6.3000 Signal Processing | 6.3000 Signal Processing]]</span>
<span class="sus-course">[[🎓Universities/MIT/16.420 Planning Under Uncertainty | 16.420 Planning Under Uncertainty]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4400 Computer Graphics | 6.4400 Computer Graphics]]</span>

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