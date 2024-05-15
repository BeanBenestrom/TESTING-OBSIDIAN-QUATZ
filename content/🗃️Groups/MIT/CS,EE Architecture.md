<span class="sus-course">[[🎓Universities/MIT/6.1920 Constructive Computer Architecture | 6.1920 Constructive Computer Architecture]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2050 Digital Systems Laboratory | 6.2050 Digital Systems Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2060 Microcomputer Project Laboratory | 6.2060 Microcomputer Project Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5890 | 6.5890]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5900 Computer System Architecture | 6.5900 Computer System Architecture]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5930 Hardware Architecture for Deep Learning | 6.5930 Hardware Architecture for Deep Learning]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5930 Hardware Architecture for Deep Learning | 6.5930 Hardware Architecture for Deep Learning]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5950 Secure Hardware Design | 6.5950 Secure Hardware Design]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S984 Special Subject in Electrical Engineering and Computer Science | 6.S984 Special Subject in Electrical Engineering and Computer Science]]</span>
At most one can be from 6.111, 6.2050, 6.115, 6.2060

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