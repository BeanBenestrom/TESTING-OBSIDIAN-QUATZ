<span class="sus-course">[[🎓Universities/MIT/6.3000 Signal Processing | 6.3000 Signal Processing]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3010 Signals, Systems and Inference | 6.3010 Signals, Systems and Inference]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.15J Networks | 14.15J Networks]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3720 Introduction to Statistical Data Analysis | 6.3720 Introduction to Statistical Data Analysis]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3900 Introduction to Machine Learning | 6.3900 Introduction to Machine Learning]]</span>
<span class="sus-course">[[🎓Universities/MIT/16.420 Planning Under Uncertainty | 16.420 Planning Under Uncertainty]]</span>
<span class="sus-course">[[🎓Universities/MIT/16.405J Robotics, Science and Systems | 16.405J Robotics, Science and Systems]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4210 Robotic Manipulation | 6.4210 Robotic Manipulation]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.7120 Principles of Modeling, Computing and Control for Decarbonized Electric Energy Systems | 6.7120 Principles of Modeling, Computing and Control for Decarbonized Electric Energy Systems]]</span>
<span class="sus-course">[[🎓Universities/MIT/15.093J Optimization Methods | 15.093J Optimization Methods]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8300 Advances in Computer Vision | 6.8300 Advances in Computer Vision]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.C01 Modeling with Machine Learning, from Algorithms to Applications | 6.C01 Modeling with Machine Learning, from Algorithms to Applications]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S052 Special Subject in Electrical Engineering and Computer Science | 6.S052 Special Subject in Electrical Engineering and Computer Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/2.C27J Computational Imaging, Physics and Algorithms | 2.C27J Computational Imaging, Physics and Algorithms]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.C01 Modeling with Machine Learning, from Algorithms to Applications | 6.C01 Modeling with Machine Learning, from Algorithms to Applications]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S952 Special Subject in Electrical Engineering and Computer Science | 6.S952 Special Subject in Electrical Engineering and Computer Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S059 Special Subject in Electrical Engineering and Computer Science | 6.S059 Special Subject in Electrical Engineering and Computer Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S953 Special Subject in Electrical Engineering and Computer Science | 6.S953 Special Subject in Electrical Engineering and Computer Science]]</span>

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