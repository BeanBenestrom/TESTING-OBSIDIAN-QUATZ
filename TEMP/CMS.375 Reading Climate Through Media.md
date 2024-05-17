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

catalog [CMS.375](http://student.mit.edu/catalog/mCMSa.html#CMS.375), [CMS.875](http://student.mit.edu/catalog/mCMSa.html#CMS.875)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq71_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq71_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq71_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq71_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Explores how climate is construed in the contemporary media in order to gain a better understanding of how views of climate change are shaped and received in the public sphere. Studies the pathways that take us from climate science to media content, from the big data of global scale to the particulars and narratives of the human experience. Surveys a variety of media forms--reports, articles, comics, videos, films, photography, poetry and fiction--that reflect on the contemporary human challenges of dealing with a changing natural environment of our own making. Emphasizes the role of media in shaping public opinion, both in the US and globally, and its influence on public (and voter) perceptions on which a vast body of regulation and funding for environmental management is based. Students work individually and in teams to produce a selection of the media forms studied. Students taking graduate version complete additional assignments. Limited to 20.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq71_0`, {timeout:5});
COURSE_MODULE.evaluate_req("71_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("71_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
