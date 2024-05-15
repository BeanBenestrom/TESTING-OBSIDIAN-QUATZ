<span class="sus-course">[[🎓Universities/MIT/6.1600 Foundations of Computer Security | 6.1600 Foundations of Computer Security]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.1810 Operating System Engineering | 6.1810 Operating System Engineering]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.1820J Mobile and Sensor Computing | 6.1820J Mobile and Sensor Computing]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5610 Applied Cryptography and Security | 6.5610 Applied Cryptography and Security]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5660 Computer Systems Security | 6.5660 Computer Systems Security]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5810 Operating System Engineering | 6.5810 Operating System Engineering]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5820 Computer Networks | 6.5820 Computer Networks]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5830 Database Systems | 6.5830 Database Systems]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5830 Database Systems | 6.5830 Database Systems]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5840 Distributed Computer Systems Engineering | 6.5840 Distributed Computer Systems Engineering]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5850 Principles of Computer Systems | 6.5850 Principles of Computer Systems]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S079 Special Subject in Electrical Engineering and Computer Science | 6.S079 Special Subject in Electrical Engineering and Computer Science]]</span>

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