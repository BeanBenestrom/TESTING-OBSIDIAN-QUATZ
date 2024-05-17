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

catalog [CMS.407](http://student.mit.edu/catalog/mCMSa.html#CMS.407)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq75_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq75_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq75_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq75_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Explores the ways in which humans experience the realm of sound and how perceptions and technologies of sound emerge from cultural, economic, and historical worlds. Examines how environmental, linguistic, and musical sounds are construed cross-culturally. Describes the rise of telephony, architectural acoustics, and sound recording, and the globalized travel of these technologies. Addresses questions of ownership, property, authorship, and copyright in the age of digital file sharing. Particular focus on how the sound/noise boundary is imagined, created and modeled across diverse sociocultural and scientific contexts. Auditory examples--sound art, environmental recordings, music--will be provided and invited. Instruction and practice in written and oral communication provided. Limited to 20.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq75_0`, {timeout:5});
COURSE_MODULE.evaluate_req("75_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("75_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
