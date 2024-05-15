catalog: [degree_requirements](https://eecsis.mit.edu/degree_requirements.html#II)

<font style="color: grey">Independent inquiry. Also see **grad_II** list below. A subject provides an II experience if at least 40% of the grade in a 12-unit subject depends on a single relatively open-ended project. The student should be involved in defining the project. Projects may be done singly or in groups; they may be analytical or empirical in nature. They should be supervised in the sense that at least one milestone (proposal, outline, presentation) is evaluated and the student given feedback before the final deadline.</font>

<span class="sus-course">[[🎓Universities/MIT/6.1040 Software Design | 6.1040 Software Design]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.1060 Software Performance Engineering | 6.1060 Software Performance Engineering]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.1100 Computer Language Engineering | 6.1100 Computer Language Engineering]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.1120 Dynamic Computer Language Engineering | 6.1120 Dynamic Computer Language Engineering]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.1420 Fixed Parameter and Fine,grained Computation | 6.1420 Fixed Parameter and Fine,grained Computation]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.1820J Mobile and Sensor Computing | 6.1820J Mobile and Sensor Computing]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.1850 Computer Systems and Society | 6.1850 Computer Systems and Society]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2040 Analog Electronics Laboratory | 6.2040 Analog Electronics Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2050 Digital Systems Laboratory | 6.2050 Digital Systems Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2060 Microcomputer Project Laboratory | 6.2060 Microcomputer Project Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2220 Power Electronics Laboratory | 6.2220 Power Electronics Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2370 Modern Optics Project Laboratory | 6.2370 Modern Optics Project Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2410 Quantum Engineering Platforms | 6.2410 Quantum Engineering Platforms]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3730J Statistics, Computation and Applications | 6.3730J Statistics, Computation and Applications]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4120J Computational Cognitive Science | 6.4120J Computational Cognitive Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/16.405J Robotics, Science and Systems | 16.405J Robotics, Science and Systems]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4210 Robotic Manipulation | 6.4210 Robotic Manipulation]]</span>
<span class="sus-course">[[🎓Universities/MIT/2.0911J Computational Design and Fabrication | 2.0911J Computational Design and Fabrication]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4510 Engineering Interactive Technologies | 6.4510 Engineering Interactive Technologies]]</span>
<span class="sus-course">[[🎓Universities/MIT/2.78J Principles and Practice of Assistive Technology | 2.78J Principles and Practice of Assistive Technology]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4590J Foundations of Information Policy | 6.4590J Foundations of Information Policy]]</span>
<span class="sus-course">[[🎓Universities/MIT/20.129J Biological Circuit Engineering Laboratory | 20.129J Biological Circuit Engineering Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5150 Large,scale Symbolic Systems | 6.5150 Large,scale Symbolic Systems]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8300 Advances in Computer Vision | 6.8300 Advances in Computer Vision]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8610 Quantitative Methods for Natural Language Processing | 6.8610 Quantitative Methods for Natural Language Processing]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8700J Advanced Computational Biology, Genomes, Networks, Evolution | 6.8700J Advanced Computational Biology, Genomes, Networks, Evolution]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.9000 Engineering for Impact | 6.9000 Engineering for Impact]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.9030 Strobe Project Laboratory | 6.9030 Strobe Project Laboratory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.C01 Modeling with Machine Learning, from Algorithms to Applications | 6.C01 Modeling with Machine Learning, from Algorithms to Applications]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S052 Special Subject in Electrical Engineering and Computer Science | 6.S052 Special Subject in Electrical Engineering and Computer Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/1.C25J Real World Computation with Julia | 1.C25J Real World Computation with Julia]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.C35J Interactive Data Visualization and Society | 6.C35J Interactive Data Visualization and Society]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S041 Special Subject in Electrical Engineering and Computer Science | 6.S041 Special Subject in Electrical Engineering and Computer Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S079 Special Subject in Electrical Engineering and Computer Science | 6.S079 Special Subject in Electrical Engineering and Computer Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.UAR Seminar in Undergraduate Advanced Research | 6.UAR Seminar in Undergraduate Advanced Research]]</span>

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