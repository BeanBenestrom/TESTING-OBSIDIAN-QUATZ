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

catalog [CMS.334[J]](http://student.mit.edu/catalog/mCMSa.html#CMS.334), [21W.788[J]](http://student.mit.edu/catalog/m21Wb.html#21W.788)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq49_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq49_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq49_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq49_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Examines the history of South Asian immigration, sojourning, and settlement from the 1880s to the present. Focuses on the US as one node in the global circulation, not only of people, but of media, culture and ideas, through a broader South Asian diaspora. Considers the concept of "global media" historically; emphasis on how ideas about, and self-representations of, South Asians have circulated via books, political pamphlets, performance, film, video/cassette tapes, and the internet. Students analyze and discuss scholarly writings, archival documents, memoirs, fiction, blogs and films, and write papers drawing on course materials, lectures, and discussions. Limited to 18.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq49_0`, {timeout:5});
COURSE_MODULE.evaluate_req("49_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("49_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
