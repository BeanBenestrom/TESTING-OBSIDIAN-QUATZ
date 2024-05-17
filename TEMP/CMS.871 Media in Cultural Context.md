---
tags:
  - course
ctime: 2024-04-18T00:19:28
mstime: 2024-04-18T00:19:28
level: graduate
subject: 
university: mit
completion: open
percentage: 0
prereq: Permission of instructor
coreq: None.
---

catalog [CMS.871](http://student.mit.edu/catalog/mCMSa.html#CMS.871), [21L.715](http://student.mit.edu/catalog/m21La.html#21L.715)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq124_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq124_0">Permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq124_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq124_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Seminar uses case studies to examine specific media or media configurations and the larger social, cultural, economic, political, or technological contexts within which they operate. Organized around recurring themes in media history, as well as specific genres, movements, media, or historical moments. Previously taught topics include Gendered Genres: Horror and Maternal Melodramas; Comics, Cartoons, and Graphic Storytelling; and Exploring Children's Culture. Students taking graduate version complete additional assignments. Approved for credit in Women's and Gender Studies when content meets the requirements for subjects in that program. Limited to 12.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq124_0`, {timeout:5});
COURSE_MODULE.evaluate_req("124_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("124_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
