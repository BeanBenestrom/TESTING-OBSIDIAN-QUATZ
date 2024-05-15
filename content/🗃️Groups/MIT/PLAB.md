catalog: [degree_requirements](https://eecsis.mit.edu/degree_requirements.html#PLAB)

<font style="color: grey">Project-Based Design Laboratory for 6-2 (new)</font>

<span class="sus-course">[[🎓Universities/MIT/6.1100 Computer Language Engineering | 6.1100 Computer Language Engineering]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.1820J Mobile and Sensor Computing | 6.1820J Mobile and Sensor Computing]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2040 Analog Electronics Laboratory | 6.2040 Analog Electronics Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2050 Digital Systems Laboratory | 6.2050 Digital Systems Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2060 Microcomputer Project Laboratory | 6.2060 Microcomputer Project Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2220 Power Electronics Laboratory | 6.2220 Power Electronics Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2220 Power Electronics Laboratory | 6.2220 Power Electronics Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2370 Modern Optics Project Laboratory | 6.2370 Modern Optics Project Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2410 Quantum Engineering Platforms | 6.2410 Quantum Engineering Platforms]]</span>
<span class="sus-course">[[🎓Universities/MIT/3.155J Micro, Nano Processing Technology | 3.155J Micro, Nano Processing Technology]]</span>
<span class="sus-course">[[🎓Universities/MIT/16.405J Robotics, Science and Systems | 16.405J Robotics, Science and Systems]]</span>
<span class="sus-course">[[🎓Universities/MIT/2.0911J Computational Design and Fabrication | 2.0911J Computational Design and Fabrication]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4510 Engineering Interactive Technologies | 6.4510 Engineering Interactive Technologies]]</span>
<span class="sus-course">[[🎓Universities/MIT/21M.385J Interactive Music Systems | 21M.385J Interactive Music Systems]]</span>
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