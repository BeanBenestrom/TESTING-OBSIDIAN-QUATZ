---
tags:
  - course
ctime: 2024-04-18T00:19:29
mstime: 2024-04-18T00:19:29
level: undergraduate
subject: 
university: mit
completion: open
percentage: 0
prereq: None.
coreq: None.
---

catalog [WGS.109](http://student.mit.edu/catalog/mWGSa.html#WGS.109)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4271_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4271_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4271_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4271_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">An interdisciplinary subject that examines questions of feminism, international women's issues, and globalization through the study of novels, films, critical essays, painting and music. Considers how women redefine the notions of community and nation, how development affects their lives, and how access to the internet and to the production industry impacts women's lives. Primary topics of interest include transformations of traditional values, social change, gender role distribution, identity formation, migration flows, globalization and development, popular culture, urban life, cyber-culture, activism, and human rights. Limited to 25 when Writing Tutor is assigned to the class. Otherwise, limited to 18.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4271_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4271_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4271_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
