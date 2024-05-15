catalog: [bullein](https://catalog.mit.edu/degree-charts/physics-course-8/)

# Required Subjects
<span class="sus-course">[[🎓Universities/MIT/18.03 Differential Equations | 18.03 Differential Equations]]</span>
<span class="sus-course">[[🎓Universities/MIT/8.03 Physics III | 8.03 Physics III]]</span>
<span class="sus-course">[[🎓Universities/MIT/8.033 Relativity | 8.033 Relativity]]</span>
<span class="sus-course">[[🎓Universities/MIT/8.04 Quantum Physics I | 8.04 Quantum Physics I]]</span>
<span class="sus-course">[[🎓Universities/MIT/8.044 Statistical Physics I | 8.044 Statistical Physics I]]</span>
<span class="sus-course">[[🎓Universities/MIT/8.05 Quantum Physics II | 8.05 Quantum Physics II]]</span>
<span class="sus-course">[[🎓Universities/MIT/8.06 Quantum Physics III | 8.06 Quantum Physics III]] </span><font style="color: grey">(CI-M)</font>
<span class="sus-course">[[🎓Universities/MIT/8.13 Experimental Physics I | 8.13 Experimental Physics I]]</span> <font style="color: grey">(CI-M)</font>
<span class="sus-course">[[🎓Universities/MIT/8.14 Experimental Physics II | 8.14 Experimental Physics II]]</span>
<span class="sus-course">[[🎓Universities/MIT/8.223 Classical Mechanics II | 8.223 Classical Mechanics II]]</span>
<span class="sus-course">[[🎓Universities/MIT/8.THU Undergraduate Physics Thesis | 8.THU Undergraduate Physics Thesis]]</span>

#### Restricted Electives	
One subject in the Department of Mathematics beyond **18.03**
Two subjects in the Department of Physics in addition to those listed above, including at least one of the following:
<span class="sus-course">[[🎓Universities/MIT/8.07 Electromagnetism II | 8.07 Electromagnetism II]]</span>
<span class="sus-course">[[🎓Universities/MIT/8.08 Statistical Physics II | 8.08 Statistical Physics II]]</span>
<span class="sus-course">[[🎓Universities/MIT/8.09 Classical Mechanics III | 8.09 Classical Mechanics III]]</span>

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