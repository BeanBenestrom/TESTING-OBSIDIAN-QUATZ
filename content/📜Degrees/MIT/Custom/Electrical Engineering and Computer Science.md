based upon: [[📜Degrees/MIT/Electrical Engineering and Computer Science|Electrical Engineering and Computer Science]]

# Requirements (2022)

#### Four fundamental subjects

<span class="sus-course">[[🎓Universities/MIT/6.100A Introduction to Computer Science Programming in Python|6.100A Introduction to Computer Science Programming in Python]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.062J Mathematics for Computer Science | 6.1200 Mathematics for Computer Science]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.1903 Introduction to Low,level Programming in C and Assembly | 6.1903 Introduction to Low,level Programming in C and Assembly]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.1210 Introduction to Algorithms | 6.1210 Introduction to Algorithms]]</span>

#### Two math subjects
<span class="sus-course">[[🎓Universities/MIT/18.06 Linear Algebra | 18.06 Linear Algebra]]</span>
One of 
<span class="sus-course">[[🎓Universities/MIT/6.041 Probabilistic Systems Analysis and Applied Probability | 6.041 Probabilistic Systems Analysis and Applied Probability]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.05 Introduction to Probability and Statistics | 18.05 Introduction to Probability and Statistics]]</span>

#### Four system design subjects
<span class="sus-course">[[🎓Universities/MIT/6.1910 Computation Structures|6.1910 Computation Structures]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2000 Electrical Circuits, Modeling and Design of Physical Systems|6.2000 Electrical Circuits, Modeling and Design of Physical Systems]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.3100 Dynamical System Modeling and Control Design| 6.3100 Dynamical System Modeling and Control Design]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.9000 Engineering for Impact | 6.9000 Engineering for Impact]]</span>

#### Six elective subjects
<span class="sus-course">[[🎓Universities/MIT/2.007 Design and Manufacturing I | 2.007 Design and Manufacturing I]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.1100 Computer Language Engineering | 6.1100 Computer Language Engineering]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4210 Robotic Manipulation | 6.4210 Robotic Manipulation]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.2050 Digital Systems Laboratory | 6.2050 Digital Systems Laboratory]]</span> --> 6.111 Introductory Digital Systems Laboratory
<span class="sus-course">[[🎓Universities/MIT/6.5930 Hardware Architecture for Deep Learning | 6.5930 Hardware Architecture for Deep Learning]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.1810 Operating System Engineering | 6.1810 Operating System Engineering]]</span> --> *graduate* 6.828 Operating System Engineering

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

EECS:
✔️ [2.007 Design and Manufacturing I](https://ocw.mit.edu/courses/2-007-design-and-manufacturing-i-spring-2009/pages/related-resources/)
✔️ [18.404 Theory of Computation](https://ocw.mit.edu/courses/18-404j-theory-of-computation-fall-2020/)
6.1040 Software Design
✔️ 6.1100 Computer Language Engineering 
--> [6.035 Computer Language Engineering](https://ocw.mit.edu/courses/6-035-computer-language-engineering-spring-2010/)
--> [6.035 Computer Language Engineering (SMA 5502)](https://ocw.mit.edu/courses/6-035-computer-language-engineering-sma-5502-fall-2005/)
6.1120 Dynamic Computer Language Engineering
6.1600 Foundations of Computer Security

EE Track:
6.7411 Principles of Digital Communication 
6.3900 Introduction to Machine Learning 
✔️ [6.4210 Robotic Manipulation](https://ocw.mit.edu/courses/6-4210-robotic-manipulation-fall-2022/)
6.2050 Digital Systems Laboratory --> ✔️ [6.111 Introductory Digital Systems Laboratory](https://ocw.mit.edu/courses/6-111-introductory-digital-systems-laboratory-spring-2006/)
✔️ [6.5930 Hardware Architecture for Deep Learning](http://student.mit.edu/catalog/search.cgi?search=6.5930) http://csg.csail.mit.edu/6.5930/info.html
[6.1810 Operating System Engineering](http://student.mit.edu/catalog/search.cgi?search=6.1810) --> ✔️ graduate [6.828 Operating System Engineering](https://ocw.mit.edu/courses/6-828-operating-system-engineering-fall-2012/)
[6.5820 Computer Networks](http://student.mit.edu/catalog/search.cgi?search=6.5820)
[6.2060 Microcomputer Project Laboratory](http://student.mit.edu/catalog/search.cgi?search=6.2060)