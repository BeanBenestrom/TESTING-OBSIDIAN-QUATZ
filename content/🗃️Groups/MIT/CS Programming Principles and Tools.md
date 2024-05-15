<span class="sus-course">[[🎓Universities/MIT/6.1040 Software Design | 6.1040 Software Design]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.1060 Software Performance Engineering | 6.1060 Software Performance Engineering]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.1100 Computer Language Engineering | 6.1100 Computer Language Engineering]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.1120 Dynamic Computer Language Engineering | 6.1120 Dynamic Computer Language Engineering]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5060 Algorithm Engineering | 6.5060 Algorithm Engineering]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5080 Multicore Programming | 6.5080 Multicore Programming]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5080 Multicore Programming | 6.5080 Multicore Programming]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5110 Foundations of Program Analysis | 6.5110 Foundations of Program Analysis]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5120 Formal Reasoning About Programs | 6.5120 Formal Reasoning About Programs]]</span>

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