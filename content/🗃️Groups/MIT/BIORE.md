catalog: [degree_requirements](https://eecsis.mit.edu/degree_requirements.html#BIORE)

<font style="color: grey">Biology restricted electives</font>

<span class="sus-course">[[🎓Universities/MIT/1.018J Fundamentals of Ecology | 1.018J Fundamentals of Ecology]]</span>
<span class="sus-course">[[🎓Universities/MIT/10.441J Molecular and Engineering Aspects of Biotechnology | 10.441J Molecular and Engineering Aspects of Biotechnology]]</span>
<span class="sus-course">[[🎓Universities/MIT/11.134J Infections and Inequalities, Interdisciplinary Perspectives on Global Health | 11.134J Infections and Inequalities, Interdisciplinary Perspectives on Global Health]]</span>
<span class="sus-course">[[🎓Universities/MIT/1.018J Fundamentals of Ecology | 1.018J Fundamentals of Ecology]]</span>
<span class="sus-course">[[🎓Universities/MIT/20.230J Immunology | 20.230J Immunology]]</span>
<span class="sus-course">[[🎓Universities/MIT/10.441J Molecular and Engineering Aspects of Biotechnology | 10.441J Molecular and Engineering Aspects of Biotechnology]]</span>
<span class="sus-course">[[🎓Universities/MIT/5.08J Fundamentals of Chemical Biology | 5.08J Fundamentals of Chemical Biology]]</span>
<span class="sus-course">[[🎓Universities/MIT/6.4710J Evolutionary Biology, Concepts, Models and Computation | 6.4710J Evolutionary Biology, Concepts, Models and Computation]]</span>
<span class="sus-course">[[🎓Universities/MIT/5.08J Fundamentals of Chemical Biology | 5.08J Fundamentals of Chemical Biology]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.093 Modern Biostatistics | 7.093 Modern Biostatistics]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.094 Modern Computational Biology | 7.094 Modern Computational Biology]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.20J Human Physiology | 7.20J Human Physiology]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.21 Microbial Physiology | 7.21 Microbial Physiology]]</span>
<span class="sus-course">[[🎓Universities/MIT/20.230J Immunology | 20.230J Immunology]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.26 Molecular Basis of Infectious Disease | 7.26 Molecular Basis of Infectious Disease]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.27 Principles of Human Disease and Aging | 7.27 Principles of Human Disease and Aging]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.28 Molecular Biology | 7.28 Molecular Biology]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.29J Cellular and Molecular Neurobiology | 7.29J Cellular and Molecular Neurobiology]]</span>
<span class="sus-course">[[🎓Universities/MIT/1.018J Fundamentals of Ecology | 1.018J Fundamentals of Ecology]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.31 Current Topics in Mammalian Biology, Medical Implications | 7.31 Current Topics in Mammalian Biology, Medical Implications]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.32 Systems Biology | 7.32 Systems Biology]]</span>
<span class="sus-course">[[🎓Universities/MIT/10.441J Molecular and Engineering Aspects of Biotechnology | 10.441J Molecular and Engineering Aspects of Biotechnology]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.371 Biological and Engineering Principles Underlying Novel Biotherapeutics | 7.371 Biological and Engineering Principles Underlying Novel Biotherapeutics]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.45 The Hallmarks of Cancer | 7.45 The Hallmarks of Cancer]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.46 Building with Cells | 7.46 Building with Cells]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.49J Developmental Neurobiology | 7.49J Developmental Neurobiology]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.32 Systems Biology | 7.32 Systems Biology]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.29J Cellular and Molecular Neurobiology | 7.29J Cellular and Molecular Neurobiology]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.49J Developmental Neurobiology | 7.49J Developmental Neurobiology]]</span>
<span class="sus-course">[[🎓Universities/MIT/11.134J Infections and Inequalities, Interdisciplinary Perspectives on Global Health | 11.134J Infections and Inequalities, Interdisciplinary Perspectives on Global Health]]</span>
<span class="sus-course">[[🎓Universities/MIT/7.20J Human Physiology | 7.20J Human Physiology]]</span>

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