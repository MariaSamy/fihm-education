# Indian Medicines 🌿

A free beginner-friendly bilingual (English + Tamil) educational web app for learning about Indian medicinal plants.

## Features
- Mobile-responsive lessons and plant cards
- English, Tamil, and botanical plant names
- Traditional uses distinguished from scientific evidence
- Practical activities with browser-saved checklists
- Interactive quizzes and scientific references
- No login or paid API required

## Publish the next lesson
1. Duplicate `lessons/lesson-001.json` as `lessons/lesson-002.json`.
2. Update lesson title, date, learning objectives, plant profiles, quiz, examples, safety and credible references.
3. Append an entry in `lessons/index.json` with `id`, `file`, `title`, `week` and `published: true`.
4. Commit to the branch and merge into `main`.

The web app automatically reads the updated lesson catalog. The GitHub Actions workflow deploys new published lessons after each push to main. Lesson authoring and evidence review are separate tasks; deployment alone does not generate medically reviewed lessons.

## Publish the website
1. Merge the Indian Medicines pull request into `main`.
2. In GitHub repository **Settings → Pages**, set **Source** to **GitHub Actions**.
3. Run **Deploy Medicinal Plants Web App** in **Actions**, if needed.
4. Expected site, once enabled and deployed: https://mariasamy.github.io/fihm-education/

## Safety
Educational content only. Do not self-diagnose, take unknown herbs or replace prescribed medical treatment. User quiz and activity progress remains in the current browser.
