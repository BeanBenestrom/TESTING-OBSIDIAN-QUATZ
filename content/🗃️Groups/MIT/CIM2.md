catalog: [degree_requirements](https://eecsis.mit.edu/degree_requirements.html#CIM2)

<font style="color: grey">EECS CI-M subjects</font>

<span class="sus-course">[[🎓Universities/MIT/6.1800 Computer Systems Engineering | 6.1800 Computer Systems Engineering]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.1850 Computer Systems and Society | 6.1850 Computer Systems and Society]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2040 Analog Electronics Laboratory | 6.2040 Analog Electronics Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2050 Digital Systems Laboratory | 6.2050 Digital Systems Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2060 Microcomputer Project Laboratory | 6.2060 Microcomputer Project Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2060 Microcomputer Project Laboratory | 6.2060 Microcomputer Project Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2220 Power Electronics Laboratory | 6.2220 Power Electronics Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2220 Power Electronics Laboratory | 6.2220 Power Electronics Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2370 Modern Optics Project Laboratory | 6.2370 Modern Optics Project Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/3.155J Micro, Nano Processing Technology | 3.155J Micro, Nano Processing Technology]]</span>
<span class="sus-course">[[🎓Universities/MIT/16.405J Robotics, Science and Systems | 16.405J Robotics, Science and Systems]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4210 Robotic Manipulation | 6.4210 Robotic Manipulation]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4590J Foundations of Information Policy | 6.4590J Foundations of Information Policy]]</span>
<span class="sus-course">[[🎓Universities/MIT/2.75J Medical Device Design | 2.75J Medical Device Design]]</span>
<span class="sus-course">[[🎓Universities/MIT/20.129J Biological Circuit Engineering Laboratory | 20.129J Biological Circuit Engineering Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8300 Advances in Computer Vision | 6.8300 Advances in Computer Vision]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8610 Quantitative Methods for Natural Language Processing | 6.8610 Quantitative Methods for Natural Language Processing]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.9030 Strobe Project Laboratory | 6.9030 Strobe Project Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.UAR Seminar in Undergraduate Advanced Research | 6.UAR Seminar in Undergraduate Advanced Research]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.UAT Oral Communication | 6.UAT Oral Communication]]</span>

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