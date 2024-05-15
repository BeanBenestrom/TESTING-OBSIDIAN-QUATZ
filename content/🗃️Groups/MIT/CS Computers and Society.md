<span class="sus-course">[[🎓Universities/MIT/6.1850 Computer Systems and Society | 6.1850 Computer Systems and Society]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4590J Foundations of Information Policy | 6.4590J Foundations of Information Policy]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8530 Interactive Data Visualization | 6.8530 Interactive Data Visualization]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.C35J Interactive Data Visualization and Society | 6.C35J Interactive Data Visualization and Society]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.C35J Interactive Data Visualization and Society | 6.C35J Interactive Data Visualization and Society]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S041 Special Subject in Electrical Engineering and Computer Science | 6.S041 Special Subject in Electrical Engineering and Computer Science]]</span>

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