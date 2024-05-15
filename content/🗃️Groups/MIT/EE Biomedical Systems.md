<span class="sus-course">[[🎓Universities/MIT/22.54J Biomedical Systems, Modeling and Inference | 22.54J Biomedical Systems, Modeling and Inference]]</span>
and one of:
<span class="sus-course">[[🎓Universities/MIT/2.791J Cellular Neurophysiology and Computing | 2.791J Cellular Neurophysiology and Computing]]</span>
<span class="sus-course">[[🎓Universities/MIT/2.792J Quantitative and Clinical Physiology | 2.792J Quantitative and Clinical Physiology]]</span>
<span class="sus-course">[[🎓Universities/MIT/2.793J Fields, Forces and Flows in Biological Systems | 2.793J Fields, Forces and Flows in Biological Systems]]</span>
<span class="sus-course">[[🎓Universities/MIT/2.75J Medical Device Design | 2.75J Medical Device Design]]</span>

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