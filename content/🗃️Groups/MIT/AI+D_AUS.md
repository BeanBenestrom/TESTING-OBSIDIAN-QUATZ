catalog: [degree_requirements](https://eecsis.mit.edu/degree_requirements.html#AI+D_AUS)

<font style="color: grey">Advanced undergraduate subjects for 6-4 students</font>

<span class="sus-course">[[🎓Universities/MIT/18.404 Theory of Computation | 18.404 Theory of Computation]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3730J Statistics, Computation and Applications | 6.3730J Statistics, Computation and Applications]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4210 Robotic Manipulation | 6.4210 Robotic Manipulation]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5150 Large,scale Symbolic Systems | 6.5150 Large,scale Symbolic Systems]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5830 Database Systems | 6.5830 Database Systems]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.7410 Principles of Digital Communication | 6.7410 Principles of Digital Communication]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.7930J Machine Learning for Healthcare | 6.7930J Machine Learning for Healthcare]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8300 Advances in Computer Vision | 6.8300 Advances in Computer Vision]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8300 Advances in Computer Vision | 6.8300 Advances in Computer Vision]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8370 Advanced Computational Photography | 6.8370 Advanced Computational Photography]]</span>
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