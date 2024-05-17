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
prereq: Permission of instructor
coreq: None.
---

catalog [CMS.628](http://student.mit.edu/catalog/mCMSa.html#CMS.628), [CMS.828](http://student.mit.edu/catalog/mCMSa.html#CMS.828)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq97_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq97_0">Permission of instructor</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq97_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq97_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Studies and develops computational identity systems for games, social media, virtual worlds, and computer-based artwork. An interdisciplinary set of readings (cognitive science, computer science, art, and sociology) looks at both the underlying technology and the social/cultural aspects of identity. Includes topics such as developing improved characters, avatars, agents, social networking profiles, and online accounts. Engages students in on-going  research projects. Explores how social categories are formed in digital media, including gender, class, and ethnicity, along with everyday social categories (such as those based on personality or shared media preferences). Experience required in one of the following: computer programming, graphic design, web development, interaction design, or social science research methods. Students taking graduate version complete additional assignments.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq97_0`, {timeout:5});
COURSE_MODULE.evaluate_req("97_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("97_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
