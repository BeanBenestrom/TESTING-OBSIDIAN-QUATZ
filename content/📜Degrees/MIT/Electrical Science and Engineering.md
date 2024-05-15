catalog: [6-1: Electrical Science and Engineering](https://www.eecs.mit.edu/academics/undergraduate-programs/curriculum/6-1-electrical-science-and-engineering/), [Bulletin](https://catalog.mit.edu/degree-charts/electrical-science-engineering-course-6-1/)

<font style="color: grey"></font><font style="color: grey">This major focuses on the study of circuits and devices, materials and nanotechnology, communications, control and signal processing, applied physics, and biological applications.</font>

# Requirements

#### One programming skills subject
6.0001
<span class="sus-course">[[🎓Universities/MIT/6.100A Introduction to Computer Science Programming in Python | 6.100A Introduction to Computer Science Programming in Python]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.100L Introduction to Computer Science and Programming | 6.100L Introduction to Computer Science and Programming]]</span>

#### One math subject
<span class="sus-course">[[🎓Universities/MIT/18.03 Differential Equations | 18.03 Differential Equations]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.032 Differential Equations | 18.032 Differential Equations]]</span>
<span class="sus-course">[[🎓Universities/MIT/CC.1803 Differential Equations | CC.1803 Differential Equations]]</span>
<span class="sus-course">[[🎓Universities/MIT/ES.1803 Differential Equations | ES.1803 Differential Equations]]</span>

#### Three foundation subject
<span class="sus-course">[[🎓Universities/MIT/6.1910 Computation Structures | 6.1910 Computation Structures]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2000 Electrical Circuits, Modeling and Design of Physical Systems | 6.2000 Electrical Circuits, Modeling and Design of Physical Systems]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3000 Signal Processing | 6.3000 Signal Processing]]</span>

#### Three header subjects
<span class="sus-course">[[🎓Universities/MIT/6.2210 Electromagnetic Fields, Forces and Motion|6.2210 Electromagnetic Fields, Forces and Motion]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2300 Electromagnetics Waves and Applications|6.2300 Electromagnetics Waves and Applications]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2500 Nanoelectronics and Computing Systems|6.2500 Nanoelectronics and Computing Systems]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3010 Signals, Systems and Inference|6.3010 Signals, Systems and Inference]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3900 Introduction to Machine Learning|6.3900 Introduction to Machine Learning]]</span>
<span class="sus-course">[[🎓Universities/MIT/2.791J Cellular Neurophysiology and Computing | 2.791J Cellular Neurophysiology and Computing]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2210 Electromagnetic Fields, Forces and Motion|6.2210 Electromagnetic Fields, Forces and Motion]]</span>

#### Six elective subjects
Two from [[AUS2]] 
Four additional from [[EECS]]

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

---

#### Additional Constraints
At least _one_ of your completed subjects must be from the [[DLAB2]]
At least _one_ of your completed subjects must be from the [[II]]
At least _one_ of your completed subjects must be from the [[PROB]]
At least _two_ of your completed subjects must be from the [[CIM2]]

#### Notes

Instead of the original "introductory subject" and "[[6.UAT Oral Communication | 6.UAT]]/[[6.UAR Seminar in Undergraduate Advanced Research | 6.UAR]]" requirements, you now get to choose two additional electives from the **EECS** list. The **CIM2** list has been expanded to include subjects that can also satisfy the **AUS2** requirement.

6-1 students who are double majoring in 8-flex may make the following substitutions to their 6-1 degree program:

- 8.03 in place of the intro subject
- 8.04 in place of 6.004
- 8.05 or 8.051 as one of their header subjects