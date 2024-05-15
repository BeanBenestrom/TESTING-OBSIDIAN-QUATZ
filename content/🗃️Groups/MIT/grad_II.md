catalog: [degree_requirements](https://eecsis.mit.edu/degree_requirements.html#grad_II)

<font style="color: grey">Graduate subjects that satisfy the **II** additional constraint.</font>

<span class="sus-course">[[🎓Universities/MIT/6.3730J Statistics, Computation and Applications | 6.3730J Statistics, Computation and Applications]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4210 Robotic Manipulation | 6.4210 Robotic Manipulation]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5150 Large,scale Symbolic Systems | 6.5150 Large,scale Symbolic Systems]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5610 Applied Cryptography and Security | 6.5610 Applied Cryptography and Security]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5690 | 6.5690]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8300 Advances in Computer Vision | 6.8300 Advances in Computer Vision]]</span>
<span class="sus-course">[[🎓Universities/MIT/2.0911J Computational Design and Fabrication | 2.0911J Computational Design and Fabrication]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8510 Intelligent Multimodal User Interfaces | 6.8510 Intelligent Multimodal User Interfaces]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8530 Interactive Data Visualization | 6.8530 Interactive Data Visualization]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8610 Quantitative Methods for Natural Language Processing | 6.8610 Quantitative Methods for Natural Language Processing]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8700J Advanced Computational Biology, Genomes, Networks, Evolution | 6.8700J Advanced Computational Biology, Genomes, Networks, Evolution]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.C01 Modeling with Machine Learning, from Algorithms to Applications | 6.C01 Modeling with Machine Learning, from Algorithms to Applications]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S952 Special Subject in Electrical Engineering and Computer Science | 6.S952 Special Subject in Electrical Engineering and Computer Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.C35J Interactive Data Visualization and Society | 6.C35J Interactive Data Visualization and Society]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S893 Special Subject in Electrical Engineering and Computer Science | 6.S893 Special Subject in Electrical Engineering and Computer Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S953 Special Subject in Electrical Engineering and Computer Science | 6.S953 Special Subject in Electrical Engineering and Computer Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S977 Special Subject in Electrical Engineering and Computer Science | 6.S977 Special Subject in Electrical Engineering and Computer Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S984 Special Subject in Electrical Engineering and Computer Science | 6.S984 Special Subject in Electrical Engineering and Computer Science]]</span>

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