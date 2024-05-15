One of:
<span class="sus-course">[[🎓Universities/MIT/18.410J Design and Analysis of Algorithms | 18.410J Design and Analysis of Algorithms]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3000 Signal Processing | 6.3000 Signal Processing]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3100 Dynamical System Modeling and Control Design | 6.3100 Dynamical System Modeling and Control Design]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.15J Networks | 14.15J Networks]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3720 Introduction to Statistical Data Analysis | 6.3720 Introduction to Statistical Data Analysis]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3900 Introduction to Machine Learning | 6.3900 Introduction to Machine Learning]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3950 AI, Decision Making, and Society | 6.3950 AI, Decision Making, and Society]]</span>
<span class="sus-course">[[🎓Universities/MIT/16.420 Planning Under Uncertainty | 16.420 Planning Under Uncertainty]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4120J Computational Cognitive Science | 6.4120J Computational Cognitive Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4400 Computer Graphics | 6.4400 Computer Graphics]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4590J Foundations of Information Policy | 6.4590J Foundations of Information Policy]]</span>
<span class="sus-course">[[🎓Universities/MIT/15.093J Optimization Methods | 15.093J Optimization Methods]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.C01 Modeling with Machine Learning, from Algorithms to Applications | 6.C01 Modeling with Machine Learning, from Algorithms to Applications]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S052 Special Subject in Electrical Engineering and Computer Science | 6.S052 Special Subject in Electrical Engineering and Computer Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.C35J Interactive Data Visualization and Society | 6.C35J Interactive Data Visualization and Society]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.C01 Modeling with Machine Learning, from Algorithms to Applications | 6.C01 Modeling with Machine Learning, from Algorithms to Applications]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S952 Special Subject in Electrical Engineering and Computer Science | 6.S952 Special Subject in Electrical Engineering and Computer Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S041 Special Subject in Electrical Engineering and Computer Science | 6.S041 Special Subject in Electrical Engineering and Computer Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S059 Special Subject in Electrical Engineering and Computer Science | 6.S059 Special Subject in Electrical Engineering and Computer Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4120J Computational Cognitive Science | 6.4120J Computational Cognitive Science]]</span>
and one of:
<span class="sus-course">[[🎓Universities/MIT/18.404 Theory of Computation | 18.404 Theory of Computation]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3730J Statistics, Computation and Applications | 6.3730J Statistics, Computation and Applications]]</span>
<span class="sus-course">[[🎓Universities/MIT/16.405J Robotics, Science and Systems | 16.405J Robotics, Science and Systems]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4210 Robotic Manipulation | 6.4210 Robotic Manipulation]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4210 Robotic Manipulation | 6.4210 Robotic Manipulation]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5150 Large,scale Symbolic Systems | 6.5150 Large,scale Symbolic Systems]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5830 Database Systems | 6.5830 Database Systems]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.7410 Principles of Digital Communication | 6.7410 Principles of Digital Communication]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.7930J Machine Learning for Healthcare | 6.7930J Machine Learning for Healthcare]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8300 Advances in Computer Vision | 6.8300 Advances in Computer Vision]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8300 Advances in Computer Vision | 6.8300 Advances in Computer Vision]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8300 Advances in Computer Vision | 6.8300 Advances in Computer Vision]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8370 Advanced Computational Photography | 6.8370 Advanced Computational Photography]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8610 Quantitative Methods for Natural Language Processing | 6.8610 Quantitative Methods for Natural Language Processing]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8610 Quantitative Methods for Natural Language Processing | 6.8610 Quantitative Methods for Natural Language Processing]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8700J Advanced Computational Biology, Genomes, Networks, Evolution | 6.8700J Advanced Computational Biology, Genomes, Networks, Evolution]]</span>
<span class="sus-course">[[🎓Universities/MIT/20.390J Computational Systems Biology, Deep Learning in the Life Sciences | 20.390J Computational Systems Biology, Deep Learning in the Life Sciences]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S079 Special Subject in Electrical Engineering and Computer Science | 6.S079 Special Subject in Electrical Engineering and Computer Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S963,6.S967 Special Studies, EECS | 6.S963,6.S967 Special Studies, EECS]]</span>

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