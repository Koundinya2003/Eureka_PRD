<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/readme/01_hero_dark.svg">
  <img src="docs/readme/01_hero_light.svg" width="100%" alt="Eureka by ALLEN, a product teardown. A brilliant learning idea hiding behind too much friction. Eureka is an active learning system for Class 10 board prep that replaces passive lectures and rote memorisation with animated storytelling, interactive prompts and guided problem solving, so understanding feels more like following a narrative than attending a class. Core question: can users discover Eureka's magic before they hit friction? Built from a 7 slide visual teardown and a 1 page written report. An illustrated phone screen shows the proposed language picker at onboarding, cycling through English, Hindi, Telugu, Tamil, Marathi and Bengali.">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/readme/02_strengths_dark.svg">
  <img src="docs/readme/02_strengths_light.svg" width="100%" alt="Chapter 1, what works: the moment learning begins, the product shines. Each subject is its own narrative universe: The Chosen One for Maths (Real Numbers becomes an epic journey), The Legend of Zing for Chemistry, Bio Scope for Biology, and Light at the Museum for Physics. Storytelling is central to Eureka, not just a feature, and is its strongest differentiator against competitors. The Watch, Learn, Ace framework is a three tab loop on every course page: a story driven video, then structured notes plus bonus content, then MCQ and written tests with badge rewards, so learning has a clear arc, not just a playlist. Also working: strong visual and animated explanations; teacher credibility through profile pages with photo, 6 to 10+ years of experience, teaching philosophy and chapter list, real people rather than avatars; 24/7 AI doubt support; and ALLEN's 35+ year legacy and brand trust.">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/readme/03_landscape_dark.svg">
  <img src="docs/readme/03_landscape_light.svg" width="100%" alt="Chapter 2, why it stands out. Most edtech platforms optimise for content volume and exam drilling. Eureka optimises for engagement and conceptual clarity, sitting at the intersection of gamified edtech and proven ALLEN coaching fundamentals. A radar chart from the report compares engagement style against content depth on five axes scored 0 to 4: Eureka scores story led 3.8, AI doubts 3.5, mock tests 3.0, live tutors 1.2 and free access 1.0. BYJU'S scores story led 2.5, AI doubts 2.0, free access 3.0, live tutors 2.2 and mock tests 2.8. Khan Academy scores story led 1.8, AI doubts 1.5, free access 4.0, live tutors 1.0 and mock tests 1.5. These are the teardown author's qualitative scores. Key insight: story led learning is Eureka's strongest differentiator; every chapter follows a consistent narrative arc, more immersive than lecture first platforms.">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/readme/04_friction_dark.svg">
  <img src="docs/readme/04_friction_light.svg" width="100%" alt="Chapter 3, where friction begins: before value is proven, the product asks for commitment. The funnel today: install app, create account, trial and upsell, watch lesson, experience Eureka. Trial pressure and enrollment asks appear within minutes, before meaningful learning, shown by an in app banner reading Trial ends in 06d 21h 35m with an Enroll Now button. The strongest part of the product appears after onboarding, so urgency appears before trust. Second friction: language. Chapters are English first. Students who learn best in Hindi, Telugu, Tamil or Marathi hit a comprehension wall before they reach the value; the language barrier appears before product understanding, students lose confidence early and confusion replaces curiosity.">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/readme/05_recommendation_dark.svg">
  <img src="docs/readme/05_recommendation_light.svg" width="100%" alt="Chapter 4, the opportunity: speak their language first. Before confusion begins, speak their language. Recommendation 1, a language picker at onboarding (screen 1): during the very first session ask the student to choose a preferred language for explanations (English, Hindi, Telugu, Tamil, Marathi or Bengali) and store it on the user profile, which today shows class and grade but no language preference. One question, one screen, zero friction added. Metric: percentage of users who choose a language other than English, a proxy for latent demand. Recommendation 2, bilingual notes first, dubbed audio second: the Learn tab already has a Notes section, so translated concept notes are low cost (text, not a new recording) and ship faster; Watch tab videos can add a language toggle in a later sprint. Metric: notes open rate by language segment against the English only baseline. Recommendation 3, doubt resolution in the preferred language: a language aware doubt chat using LLM powered responses, so a question asked in Hindi gets an answer in Hindi. Metric: support ticket volume drop and session length increase after launch. The proposed order: pick a language, learn, then choose. Expected outcome: students experience value sooner, understand faster and build trust before being asked to commit.">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/readme/06_metrics_close_dark.svg">
  <img src="docs/readme/06_metrics_close_light.svg" width="100%" alt="Chapter 5, how success is measured: 1 the percentage of users selecting a language other than English, a proxy for latent demand; 2 notes open rate by language segment against the English baseline; 3 session duration growth after the language launch; 4 conversion rate after the first lesson is experienced; 5 support ticket drop after the language doubt launch. The chain: understanding builds confidence, confidence drives engagement, engagement drives conversion. Closing line: Let Eureka prove itself. Let them learn, then let them choose. The opportunity is not to change how students learn but to remove what prevents them from learning. The strongest path to conversion is not persuasion, it is comprehension.">
</picture>

# Eureka by ALLEN: Product Teardown

A first hand product teardown of Eureka, ALLEN's Class 10 board prep app. It looks at the gap between the product's strong pedagogy and its weaker onboarding and monetization design, and proposes a localization fix.

> An independent product management exercise. It is not affiliated with or endorsed by ALLEN.

## Contents

* [`Eureka Unlocking Magic Presentation.pdf`](./Eureka%20Unlocking%20Magic%20Presentation.pdf): 7 slide visual teardown covering onboarding, pedagogical strengths, the friction points (premature upsell, English only content), and the recommended opportunity.
* [`1 Page report.pdf`](./1%20Page%20report.pdf): 1 page written summary covering product understanding, biggest strength, biggest weakness, and the one recommendation.
* [`Latex_report`](./Latex_report): the LaTeX source of the 1 page report.
* [`docs/readme/`](docs/readme): the panels at the top of this page, the one sheet they are built from (`one_sheet.html`) and the build script.

## TL;DR

Eureka's story led, narrative driven lessons are its strongest differentiator in Indian EdTech. But the funnel asks for commitment (trial or enrollment) before students experience that value, and English first content creates a comprehension wall for learners who are not English first. The recommendation: let students experience the product in their language before asking them to commit.

## The recommendation in brief

* **Language picker at onboarding.** One screen in the first session (English, Hindi, Telugu, Tamil, Marathi, Bengali), stored on the profile. Metric: share of users choosing a language other than English.
* **Bilingual notes first, dubbed audio second.** Translated concept notes ship faster than rerecorded video. Metric: notes open rate by language segment.
* **AI doubts in the local language.** LLM powered doubt answers in the student's preferred language. Metric: session duration and support ticket drop.

## Rebuilding the panels

Edit `docs/readme/one_sheet.html`, then run:

```bash
node docs/readme/build_readme_svgs.js docs/readme/one_sheet.html docs/readme 960
```

This needs Node with Playwright installed, plus curl (fonts are fetched from Google Fonts and embedded). Each panel is written in a light and a dark version.

## Author

Aditya K Koundinya. [GitHub](https://github.com/Koundinya2003)
