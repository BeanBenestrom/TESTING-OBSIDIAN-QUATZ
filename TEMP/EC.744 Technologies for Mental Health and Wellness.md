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

catalog [EC.744](http://student.mit.edu/catalog/mECa.html#EC.744), [EC.794](http://student.mit.edu/catalog/mECa.html#EC.794)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq3871_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq3871_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq3871_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq3871_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Introduction to new technologies used in the practice of psychiatry and psychology, with emphasis on mental health and wellness. Discusses the effect of technology on mental health and the human experience. Topics include social identity and connection, mood and anxiety disorders, sleep and dreams, chronobiology, addiction and substance abuse, behavior medicine, and wellness activities such as meditation. Guest lectures from domain-expert doctors and reading assignments identify current needs and challenges found in clinical practice. Reviews emerging technologies being applied to mental health, including chatbots, social robots, wearable sensors, AI, virtual reality, biofeedback, neuromodulation, and mobile phone phenotyping. Topics of privacy and ethical use discussed. Students complete readings and weekly written assignments and three group design projects. Students taking graduate version complete additional assignments.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq3871_0`, {timeout:5});
COURSE_MODULE.evaluate_req("3871_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("3871_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
