catalog: [6-4: Artificial Intelligence and Decision Making](https://www.eecs.mit.edu/academics/undergraduate-programs/curriculum/6-4-artificial-intelligence-and-decision-making/), [bulletin](https://catalog.mit.edu/degree-charts/artifical-intelligence-decision-making-course-6-4/)

<font style="color: grey">This major teaches students to develop techniques for the analysis and synthesis of systems that interact with an external world via perception, communication, and action, and that learn, make decisions and adapt in a changing environment. It integrates disciplines typically taught in different departments, including electrical engineering, computer science, statistics, operations research and brain and cognitive sciences</font>

# Requirements

#### One programming skills subject
<span class="sus-course">[[🎓Universities/MIT/6.100A Introduction to Computer Science Programming in Python|6.100A Introduction to Computer Science Programming in Python]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.100L Introduction to Computer Science and Programming|6.100L Introduction to Computer Science and Programming]]</span>

#### Three math subjects
<span class="sus-course">[[🎓Universities/MIT/18.062J Mathematics for Computer Science | 6.1200 Mathematics for Computer Science]]</span>

One of
<span class="sus-course">[[🎓Universities/MIT/6.S084 Special Subject in Electrical Engineering and Computer Science | 6.S084 Special Subject in Electrical Engineering and Computer Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.C06J Linear Algebra and Optimization | 18.C06 Linear Algebra and Optimization]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.06 Linear Algebra | 18.06 Linear Algebra]]</span>
One of
<span class="sus-course">[[🎓Universities/MIT/6.3700 Introduction to Probability | 6.3700 Introduction to Probability]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3800 Introduction to Inference | 6.3800 Introduction to Inference]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.05 Introduction to Probability and Statistics | 18.05 Introduction to Probability and Statistics]]</span>

#### Two foundation subjects
<span class="sus-course">[[🎓Universities/MIT/6.1010 Fundamentals of Programming | 6.1010 Fundamentals of Programming]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.1210 Introduction to Algorithms | 6.1210 Introduction to Algorithms]]</span>

#### Five Center subjects
<span class="sus-course">[[🎓Universities/MIT/18.410J Design and Analysis of Algorithms | 6.1220 Design and Analysis of Algorithms]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3000 Signal Processing|6.3000 Signal Processing]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3100 Dynamical System Modeling and Control Design | 6.3100 Dynamical System Modeling and Control Design]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.15J Networks | 6.3260 Networks]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3720 Introduction to Statistical Data Analysis | 6.3720 Introduction to Statistical Data Analysis]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3900 Introduction to Machine Learning|6.3900 Introduction to Machine Learning]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3950 AI, Decision Making, and Society | 6.3950 AI, Decision Making, and Society]]</span>
<span class="sus-course">[[🎓Universities/MIT/16.420 Planning Under Uncertainty | 6.4110 Representation, Inference, and Reasoning in AI]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4120J Computational Cognitive Science | 6.4120 Computational Cognitive Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4400 Computer Graphics | 6.4400 Computer Graphics]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4590J Foundations of Information Policy | 6.4590 Foundations of Information Policy]]</span>
<span class="sus-course">[[🎓Universities/MIT/15.093J Optimization Methods | 6.7201 Optimization Methods]]</span>
<span style="display: block; background-color: rgb(100, 100, 100, 0.2)"><span class="sus-course">[[🎓Universities/MIT/6.C01 Modeling with Machine Learning, from Algorithms to Applications | 6.C01 Modeling with Machine Learning, from Algorithms to Applications]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S052 Special Subject in Electrical Engineering and Computer Science | 6.S052 Special Subject in Electrical Engineering and Computer Science]]</span>
</span><span class="sus-course">[[🎓Universities/MIT/6.C35J Interactive Data Visualization and Society | 6.C35 Interactive Data Visualization and Society]]</span><span style="display: block; background-color: rgb(100, 100, 100, 0.2)"><span class="sus-course">[[6.C01 Modeling with Machine Learning, from Algorithms to Applications | 6.C51 Modeling with Machine Learning, from Algorithms to Applications]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S952 Special Subject in Electrical Engineering and Computer Science | 6.S952 Special Subject in Electrical Engineering and Computer Science]]</span></span><span class="sus-course">[[🎓Universities/MIT/6.S041 Special Subject in Electrical Engineering and Computer Science | 6.S041 Special Subject in Electrical Engineering and Computer Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S059 Special Subject in Electrical Engineering and Computer Science | 6.S059 Special Subject in Electrical Engineering and Computer Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4120J Computational Cognitive Science | 9.660 Computational Cognitive Science]]</span>

#### Two communication-intensive subjects
One from [[Application_CIM]] list
One additional from [[CIM2]] list

#### Two elective subjects
One additional from the [[AI+D_AUS]] or [[Application_CIM]] lists
One additional from the [[EECS]] list or a [Math (course 18) requirement](https://math.mit.edu/academics/undergrad/major/)

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
At least one of your completed subjects must be from the [[SERC]] list
At least one of your completed subjects must be from the [[Data,centric | Data-centric]] list
At least one of your completed subjects must be from the [[Model,centric | Model-centric]] list
At least one of your completed subjects must be from the [[Decision,centric | Decision-centric]] list
At least one of your completed subjects must be from the [[Computation,centric | Computation-centric]] list
At least one of your completed subjects must be from the [[Human,centric | Human-centric]] list
