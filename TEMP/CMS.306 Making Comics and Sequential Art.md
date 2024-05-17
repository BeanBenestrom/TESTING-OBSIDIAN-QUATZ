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

catalog [CMS.306](http://student.mit.edu/catalog/mCMSa.html#CMS.306), [CMS.806](http://student.mit.edu/catalog/mCMSa.html#CMS.806)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq42_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq42_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq42_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq42_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Applied introduction to comics and sequential art production. Builds skills in how to develop storylines; develop and draw characters, panels, and backgrounds; prepare for print production; and comprehend the basics of sequential language, composition, and layout. Students engage with crucial personal and political issues at stake across a range of comics genres: superhero, biographical, and countercultural. Addresses not just how we create comics, but why we create comics. Students taking graduate version complete additional assignments. Limited to 16.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq42_0`, {timeout:5});
COURSE_MODULE.evaluate_req("42_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("42_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
