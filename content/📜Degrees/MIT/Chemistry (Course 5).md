catalog: [Chemistry Major & ChemFlex Option](https://chemistry.mit.edu/academic-programs/undergraduate-programs/chemistry-major-chem-flex/), [bulletin](https://catalog.mit.edu/degree-charts/chemistry-course-5/)

#### Required Lecture Subjects

<span class="sus-course">[[🎓Universities/MIT/5.03 Principles of Inorganic Chemistry I | 5.03 Principles of Inorganic Chemistry I]]</span>
<span class="sus-course">[[🎓Universities/MIT/20.507J Introduction to Biological Chemistry | 5.07 Introduction to Biological Chemistry]]</span>
<span class="sus-course">[[🎓Universities/MIT/5.111 Principles of Chemical Science | 5.111 Principles of Chemical Science]]</span> or <span class="sus-course">[[🎓Universities/MIT/5.112 Principles of Chemical Science | 5.112 Principles of Chemical Science]]</span> or equivalent
<span class="sus-course">[[🎓Universities/MIT/5.12 Organic Chemistry I | 5.12 Organic Chemistry I]]</span>
<span class="sus-course">[[🎓Universities/MIT/5.13 Organic Chemistry II | 5.13 Organic Chemistry II]]</span>
<span class="sus-course">[[🎓Universities/MIT/5.601 Thermodynamics I | 5.601 Thermodynamics I]]</span>
<span class="sus-course">[[🎓Universities/MIT/5.602 Thermodynamics II and Kinetics | 5.602 Thermodynamics II and Kinetics]]</span>
<span class="sus-course">[[🎓Universities/MIT/5.611 Introduction to Spectroscopy | 5.611 Introduction to Spectroscopy]]</span>
<span class="sus-course">[[🎓Universities/MIT/5.612 Electronic Structure of Molecules | 5.612 Electronic Structures of Molecules]]</span>

#### Restricted Lecture Electives (select two)

<span class="sus-course">[[🎓Universities/MIT/5.04 Principles of Inorganic Chemistry II | 5.04 Principles of Inorganic Chemistry II]]</span>
<span class="sus-course">[[🎓Universities/MIT/5.08J Fundamentals of Chemical Biology | 5.08 Fundamentals of Chemical Biology]]</span>
<span class="sus-course">[[🎓Universities/MIT/5.43 Advanced Organic Chemistry | 5.43 Advanced Organic Chemistry]]</span>
<span class="sus-course">[[🎓Universities/MIT/5.62 Physical Chemistry | 5.62 Physical Chemistry II]]</span>

#### Required Laboratory Subjects (URIECA)

<span class="sus-course">[[🎓Universities/MIT/5.351 Fundamentals of Spectroscopy | 5.351 Fundamentals of Spectroscopy]]</span>
<span class="sus-course">[[🎓Universities/MIT/5.352 Synthesis of Coordination Compounds and Kinetics | 5.352 Synthesis of Coordination Compounds and Kinetics]]</span> <font style="color: grey">(CI-M)</font>
<span class="sus-course">[[🎓Universities/MIT/5.353 Macromolecular Prodrugs | 5.353 Macromolecular Prodrugs]]</span>
<span class="sus-course">[[🎓Universities/MIT/5.361 Recombinant DNA Technology | 5.361 Recombinant DNA Technology]]</span>

#### Restricted Elective Labs (choose at least three)

<span class="sus-course">[[🎓Universities/MIT/5.362 Cancer Drug Efficacy | 5.362 Cancer Drug Efficacy]]</span> <font style="color: grey">(CI-M)</font>
<span class="sus-course">[[🎓Universities/MIT/5.363 Organic Structure Determination | 5.363 Organic Structure Determination]]</span>
<span class="sus-course">[[🎓Universities/MIT/5.371 Continuous Flow Chemistry,  Sustainable Conversion of Reclaimed Vegetable Oil into Biodiesel | 5.371 Continuous Flow Chemistry,  Sustainable Conversion of Reclaimed Vegetable Oil into Biodiesel]]</span>
<span class="sus-course">[[🎓Universities/MIT/5.372 Chemistry of Renewable Energy | 5.372 Chemistry of Renewable Energy]]</span>
<span class="sus-course">[[🎓Universities/MIT/5.373 Dinitrogen Cleavage | 5.373 Dinitrogen Cleavage]]</span>
<span class="sus-course">[[🎓Universities/MIT/5.381 Quantum Dots | 5.381 Quantum Dots]]</span>
<span class="sus-course">[[🎓Universities/MIT/5.382 Time, and Frequency,resolved Spectroscopy of Photosynthesis | 5.382 Time, and Frequency,resolved Spectroscopy of Photosynthesis]]</span> <font style="color: grey">(CI-M)</font>
<span class="sus-course">[[🎓Universities/MIT/5.383 Fast,flow Peptide and Protein Synthesis | 5.383 Fast,flow Peptide and Protein Synthesis]]</span>

#### Elective Labs

All remaining URIECA modules, or:
<span class="sus-course">[[🎓Universities/MIT/5.39 Research and Communication in Chemistry | 5.39 Research and Communication in Chemistry]]</span> <font style="color: grey">(CI-M)</font>

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