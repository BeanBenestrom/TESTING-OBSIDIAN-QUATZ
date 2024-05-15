catalog: [Course 18 Option 3: Pure Option](https://math.mit.edu/academics/undergrad/major/course18/pure.html), [bulletin](https://catalog.mit.edu/degree-charts/mathematics-course-18/#theoreticalmathematicstext)

# Required Subjects

<span class="sus-course">[[🎓Universities/MIT/18.03 Differential Equations | 18.03]] or [[🎓Universities/MIT/18.032 Differential Equations | 18.032]]</span> <font style="color: grey">( formerly 18.034 ) ( Differential Equations )</font>   
<font style="color: grey">( sufficiently advanced students may substitute 18.152 or 18.303 )</font>
<span class="sus-course">[[🎓Universities/MIT/18.1002 Real Analysis | 18.100B Real Analysis]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.701 Algebra I | 18.701 Algebra I]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.702 Algebra II | 18.702 Algebra II]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.901 Introduction to Topology | 18.901 Introduction to Topology]]</span>

#### One of the following three Subjects

<span class="sus-course">[[🎓Universities/MIT/18.101 Analysis and Manifolds | 18.101 Analysis and Manifolds]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.102 Introduction to Functional Analysis | 18.102 Introduction to Functional Analysis]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.103 Fourier Analysis, Theory and Applications | 18.103 Fourier Analysis, Theory and Applications]]</span>

#### One of the following six Seminars

<span class="sus-course">[[🎓Universities/MIT/18.104 Seminar in Analysis | 18.104 Seminar in Analysis]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.504 Seminar in Logic | 18.504 Seminar in Logic]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.704 Seminar in Algebra | 18.704 Seminar in Algebra]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.784 Seminar in Number Theory | 18.784 Seminar in Number Theory]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.904 Seminar in Topology | 18.904 Seminar in Topology]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.994 Seminar in Geometry | 18.994 Seminar in Geometry]]</span>

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

#### Two Restricted Electives

Two additional 12-unit Course 18 subjects of [essentially different content](https://math.mit.edu/academics/undergrad/major/index.html#similar) with the first decimal digit one or higher.

A student may, with permission, substitute a first-year graduate subject in pure mathematics for the seminar. The graduate subject will not satisfy a CI-M requirement, however.

#### Communication-Intensive Subjects in the Major
<font style="color: red">MISSING</font>