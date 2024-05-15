catalog: [degree_requirements](https://eecsis.mit.edu/degree_requirements.html#Central_subject)

<font style="color: grey">6-4 Subjects in one of the five Centers</font>

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