<span class="sus-course">[[🎓Universities/MIT/6.1820J Mobile and Sensor Computing | 6.1820J Mobile and Sensor Computing]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2050 Digital Systems Laboratory | 6.2050 Digital Systems Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2060 Microcomputer Project Laboratory | 6.2060 Microcomputer Project Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4510 Engineering Interactive Technologies | 6.4510 Engineering Interactive Technologies]]</span>

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