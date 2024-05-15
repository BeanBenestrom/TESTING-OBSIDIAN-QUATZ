catalog: [degree_requirements](https://eecsis.mit.edu/degree_requirements.html#ECONDS)

<font style="color: grey">Economics electives in data science</font>

<span class="sus-course">[[🎓Universities/MIT/14.20 Industrial Organization, Competitive Strategy and Public Policy | 14.20 Industrial Organization, Competitive Strategy and Public Policy]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.27 Economics and E,Commerce | 14.27 Economics and E,Commerce]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.36 Advanced Econometrics | 14.36 Advanced Econometrics]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.38 Inference on Causal and Structural Parameters Using ML and AI | 14.38 Inference on Causal and Structural Parameters Using ML and AI]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.41 Public Finance and Public Policy | 14.41 Public Finance and Public Policy]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.42 Environmental Policy and Economics | 14.42 Environmental Policy and Economics]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.43J Economics of Energy, Innovation, and Sustainability | 14.43J Economics of Energy, Innovation, and Sustainability]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.44J Energy Economics and Policy | 14.44J Energy Economics and Policy]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.64 Labor Economics and Public Policy | 14.64 Labor Economics and Public Policy]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.75 Political Economy and Economic Development | 14.75 Political Economy and Economic Development]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.76 Firms, Markets, Trade and Growth | 14.76 Firms, Markets, Trade and Growth]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.43J Economics of Energy, Innovation, and Sustainability | 14.43J Economics of Energy, Innovation, and Sustainability]]</span>
<span class="sus-course">[[🎓Universities/MIT/14.44J Energy Economics and Policy | 14.44J Energy Economics and Policy]]</span>
<span class="sus-course">[[🎓Universities/MIT/15.780 Analytics of Operations Management | 15.780 Analytics of Operations Management]]</span>

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