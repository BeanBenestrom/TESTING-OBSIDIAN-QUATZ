<span class="sus-course">[[🎓Universities/MIT/18.404 Theory of Computation | 18.404 Theory of Computation]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.410J Design and Analysis of Algorithms | 18.410J Design and Analysis of Algorithms]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.400J Computability and Complexity Theory | 18.400J Computability and Complexity Theory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.1420 Fixed Parameter and Fine,grained Computation | 6.1420 Fixed Parameter and Fine,grained Computation]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5060 Algorithm Engineering | 6.5060 Algorithm Engineering]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.415J Advanced Algorithms | 18.415J Advanced Algorithms]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.416J Randomized Algorithms | 18.416J Randomized Algorithms]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5230 Advanced Data Structures | 6.5230 Advanced Data Structures]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.437J Distributed Algorithms | 18.437J Distributed Algorithms]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5310 Geometric Folding Algorithms, Linkages, Origami, Polyhedra | 6.5310 Geometric Folding Algorithms, Linkages, Origami, Polyhedra]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5320 Geometric Computing | 6.5320 Geometric Computing]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5340 Topics in Algorithmic Game Theory | 6.5340 Topics in Algorithmic Game Theory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5350 Matrix Multiplication and Graph Algorithms | 6.5350 Matrix Multiplication and Graph Algorithms]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.404 Theory of Computation | 18.404 Theory of Computation]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.405J Advanced Complexity Theory | 18.405J Advanced Complexity Theory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5420 Randomness and Computation | 6.5420 Randomness and Computation]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5430 Quantum Complexity Theory | 6.5430 Quantum Complexity Theory]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5490 | 6.5490]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.425J Cryptography and Cryptanalysis | 18.425J Cryptography and Cryptanalysis]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.5630 Advanced Topics in Cryptography | 6.5630 Advanced Topics in Cryptography]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.S895 Special Subject in Electrical Engineering and Computer Science | 6.S895 Special Subject in Electrical Engineering and Computer Science]]</span>

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