<span class="sus-course">[[🎓Universities/MIT/6.2500 Nanoelectronics and Computing Systems | 6.2500 Nanoelectronics and Computing Systems]]</span>
and one of:
<span class="sus-course">[[🎓Universities/MIT/6.2540 Nanotechnology, From Atoms to Systems | 6.2540 Nanotechnology, From Atoms to Systems]]</span>
<span class="sus-course">[[🎓Universities/MIT/3.155J Micro, Nano Processing Technology | 3.155J Micro, Nano Processing Technology]]</span>

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