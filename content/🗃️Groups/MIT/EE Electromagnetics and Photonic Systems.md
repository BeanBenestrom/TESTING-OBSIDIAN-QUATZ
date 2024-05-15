<span class="sus-course">[[🎓Universities/MIT/6.2210 Electromagnetic Fields, Forces and Motion | 6.2210 Electromagnetic Fields, Forces and Motion]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2300 Electromagnetics Waves and Applications | 6.2300 Electromagnetics Waves and Applications]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2370 Modern Optics Project Laboratory | 6.2370 Modern Optics Project Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.6330 Fundamentals of Photonics | 6.6330 Fundamentals of Photonics]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S046 Special Subject in Electrical Engineering and Computer Science | 6.S046 Special Subject in Electrical Engineering and Computer Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S976 Special Subject in Electrical Engineering and Computer Science | 6.S976 Special Subject in Electrical Engineering and Computer Science]]</span>

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