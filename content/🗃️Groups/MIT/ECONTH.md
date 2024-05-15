catalog: [degree_requirements](https://eecsis.mit.edu/degree_requirements.html#ECONTH)

<font style="color: grey">Economics electives in theory</font>

<span class="sus-course">[[🎓Universities/MIT/14.04 Intermediate Microeconomic Theory | 14.04 Intermediate Microeconomic Theory]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.12 Economic Applications of Game Theory | 14.12 Economic Applications of Game Theory]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.13 Psychology and Economics | 14.13 Psychology and Economics]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.16 Strategy and Information | 14.16 Strategy and Information]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.19 Market Design | 14.19 Market Design]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.26J Organizational Economics | 14.26J Organizational Economics]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.54 International Trade | 14.54 International Trade]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.26J Organizational Economics | 14.26J Organizational Economics]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.15J Networks | 14.15J Networks]]</span>

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