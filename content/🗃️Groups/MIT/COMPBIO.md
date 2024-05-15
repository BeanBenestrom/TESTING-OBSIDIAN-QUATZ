catalog: [degree_requirements](https://eecsis.mit.edu/degree_requirements.html#COMPBIO)

<font style="color: grey">Restricted electives in Computational Biology</font>

<span class="sus-course">[[🎓Universities/MIT/18.418J Topics in Computational Molecular Biology | 18.418J Topics in Computational Molecular Biology]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4710J Evolutionary Biology, Concepts, Models and Computation | 6.4710J Evolutionary Biology, Concepts, Models and Computation]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8700J Advanced Computational Biology, Genomes, Networks, Evolution | 6.8700J Advanced Computational Biology, Genomes, Networks, Evolution]]</span>
<span class="sus-course">[[🎓Universities/MIT/20.390J Computational Systems Biology, Deep Learning in the Life Sciences | 20.390J Computational Systems Biology, Deep Learning in the Life Sciences]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.093 Modern Biostatistics | 7.093 Modern Biostatistics]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.094 Modern Computational Biology | 7.094 Modern Computational Biology]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.418J Topics in Computational Molecular Biology | 18.418J Topics in Computational Molecular Biology]]</span>

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