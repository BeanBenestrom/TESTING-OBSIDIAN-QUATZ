---
tags:
  - course
ctime: 2024-04-18T00:19:28
mstime: 2024-04-18T00:19:28
level: undergraduate
subject: 
university: mit
completion: open
percentage: 0
prereq: None.
coreq: None.
---

catalog [CMS.341](http://student.mit.edu/catalog/mCMSa.html#CMS.341), [CMS.941](http://student.mit.edu/catalog/mCMSa.html#CMS.941)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq55_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq55_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq55_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq55_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Focuses on critical media sociology of immersive social worlds, from digital environments and avatar-based worlds to live action role-play (LARP) and theme parks. Draws on both historical and contemporary cases. Investigates key issues including communication and community; authorship and co-creativity; embodiment and identity; and ownership, governance, and management. Attention given to cultural and socio-technical nature of these environments and their ongoing construction within a broader media system. Students taking graduate version complete additional assignments. Enrollment limited to 15.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq55_0`, {timeout:5});
COURSE_MODULE.evaluate_req("55_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("55_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
