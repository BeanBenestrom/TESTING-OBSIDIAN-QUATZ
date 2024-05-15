catalog: [degree_requirements](https://eecsis.mit.edu/degree_requirements.html#BIO_AAGS)

<font style="color: grey">Approved advanced graduate subjects in biology. (Comp Bio AAGS)</font>

<span class="sus-course">[[🎓Universities/MIT/1.088 Genomics and Evolution of Infectious Disease | 1.088 Genomics and Evolution of Infectious Disease]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.418J Topics in Computational Molecular Biology | 18.418J Topics in Computational Molecular Biology]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.8700J Advanced Computational Biology, Genomes, Networks, Evolution | 6.8700J Advanced Computational Biology, Genomes, Networks, Evolution]]</span>
<span class="sus-course">[[🎓Universities/MIT/20.390J Computational Systems Biology, Deep Learning in the Life Sciences | 20.390J Computational Systems Biology, Deep Learning in the Life Sciences]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.28 Molecular Biology | 7.28 Molecular Biology]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.60 Cell Biology, Structure and Functions of the Nucleus | 7.60 Cell Biology, Structure and Functions of the Nucleus]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.21 Microbial Physiology | 7.21 Microbial Physiology]]</span>
<span class="sus-course">[[🎓Universities/MIT/18.418J Topics in Computational Molecular Biology | 18.418J Topics in Computational Molecular Biology]]</span>
<span class="sus-course">[[🎓Universities/MIT/HST.508 Evolutionary and Quantitative Genomics | HST.508 Evolutionary and Quantitative Genomics]]</span>
<span class="sus-course">[[🎓Universities/MIT/1.088 Genomics and Evolution of Infectious Disease | 1.088 Genomics and Evolution of Infectious Disease]]</span>

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