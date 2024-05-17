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

catalog [SP.256](http://student.mit.edu/catalog/mSPa.html#SP.256)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4224_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4224_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4224_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4224_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Explores the potential and pitfalls of philanthropy as a mechanism for social change. Students assess the work of community agencies to address challenges and opportunities facing MIT's neighboring communities, with particular focus on community representation, equity, and social justice. Class culminates with students making a group decision on how the Learning by Giving Foundation (which is partnering with the class) will disperse $10,000 to local community agencies. Each session includes a presentation by a local community agency, grant-making foundation, and/or individual philanthropist. Through class discussion and supporting materials, students examine the interaction between philanthropy and social change, including the role of philanthropists past and present in shaping social change and social conservatism. Subject can count toward the 6-unit discovery-focused credit limit for first-year students. Limited to 20.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4224_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4224_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4224_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
