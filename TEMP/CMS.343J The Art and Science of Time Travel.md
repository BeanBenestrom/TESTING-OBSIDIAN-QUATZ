---
tags: [course]
ctime: "2024-04-18T00:19:28"
mstime: "2024-04-18T00:19:28"

level: graduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/8.02 Physics II> and <🎓Universities/MIT/18.02 Calculus>"
coreq: "None."
---

catalog [CMS.343[J]](http://student.mit.edu/catalog/mCMSa.html#CMS.343), [2.984[J]](http://student.mit.edu/catalog/m2c.html#2.984)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq57_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq57_0">[[🎓Universities/MIT/8.02 Physics II | 8.02]] and [[🎓Universities/MIT/18.02 Calculus | 18.02]]</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq57_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq57_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Explores time travel and other physical paradoxes—black holes, wormholes, and the multiverse—in the contexts of human narrative and contemporary scientific understanding. Instruction provided in the fundamental science of time travel in relativity and quantum mechanics. Students read and view classic time travel narratives in visual art and in film, and construct their own original time travel narratives. Limited to 20.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq57_0`, {timeout:5});
COURSE_MODULE.evaluate_req("57_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("57_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
