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

catalog [SP.253](http://student.mit.edu/catalog/mSPa.html#SP.253)

<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_prereq4221_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Prerequisites</font><br><span id="prereq4221_0">None.</span></span>
<span style="display: block; padding: 15px; background-color: rgb(100, 100, 100, 0.2);"><font id="m_coreq4221_0" style="display: block; font-family: Arial, sans-serif; font-weight: bold; padding: 5px">Corequisites</font><br><span id="coreq4221_0">None.</span></span>

<font style="">Description:</font>
<font style="color: grey; font-size: 0.8rem;">Are your goals your own? Or do they represent what others wish for you to achieve? Have the evil tendrils of imposter syndrome ever plagued you? We are our own worst enemies when it comes to our success in our lives and careers. Throughout our lives, we absorb labels, identities, and imposed goals from those around us. Reflecting, and broadening these goals can help one break out of fixed thinking and start focusing on how to communicate their ideas and goals to others. This course seeks to challenge students to shift from a static mindset into one of growth, seek contentedness through purpose, and gain skills to better present themselves and their ideas. Instructional activities will include self-reflection (written/oral), interviews, alum panels, and short assignments outside the classroom. Outside assignments include individual and group work. Subject can count toward the 6-unit discovery-focused credit limit for first-year students. Limited to 25; preference for first-year students.</font>

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
await UTILITY_MODULE.waitForElements(`#m_prereq4221_0`, {timeout:5});
COURSE_MODULE.evaluate_req("4221_0", "prereq", UTILITY_MODULE, dv, tp);
COURSE_MODULE.evaluate_req("4221_0", "coreq", UTILITY_MODULE, dv, tp);
// --------------------------------
}; main();
```

---

<< HELLO, WORLD >>
