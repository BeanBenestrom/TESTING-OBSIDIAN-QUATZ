<span class="sus-course">[[🎓Universities/MIT/6.7410 Principles of Digital Communication | 6.7410 Principles of Digital Communication]]</span>
and one of:
<span class="sus-course">[[🎓Universities/MIT/6.1800 Computer Systems Engineering | 6.1800 Computer Systems Engineering]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3000 Signal Processing | 6.3000 Signal Processing]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3010 Signals, Systems and Inference | 6.3010 Signals, Systems and Inference]]</span>

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