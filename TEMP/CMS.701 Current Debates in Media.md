---
tags: [course]
ctime: "2024-04-18T00:19:28"
mstime: "2024-04-18T00:19:28"

level: undergraduate
subject: 
university: mit
completion: closed
percentage: 0
prereq: "<🎓Universities/MIT/CMS.100 Introduction to Media Studies>"
coreq: "None."
---

catalog [CMS.701](http://student.mit.edu/catalog/mCMSa.html#CMS.701), [CMS.901](http://student.mit.edu/catalog/mCMSa.html#CMS.901)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq103_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq103_0">[[🎓Universities/MIT/CMS.100 Introduction to Media Studies | CMS.100]]</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq103_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq103_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Addresses important, current debates in media with in-depth discussion of popular perceptions and policy implications. Students use multiple perspectives to analyze texts emanating from these debates, and present their findings through discussions and reports. Explores emerging topics (e.g., piracy and IP regimes, net neutrality, media effects, social media and social change, and changing literacies) across media forms and from various historical, transcultural, and methodological perspectives. Examines the framing of these issues, their ethical and policy implications, and strategies for repositioning the debate. Instruction and practice in written and oral communication provided. Students taking graduate version complete additional assignments.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq103_0`, {timeout:5});
COURSE_MODULE.evaluate_req("103_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("103_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
