# Rishabh Classes — Mock Test Website Prototype

## Run it
1. Keep `index.html`, `logo.png`, and `questions.json` together.
2. Open `index.html` in a modern browser. The question bank is embedded in the HTML so the prototype works without a server; `questions.json` is included as the editable source bank.

## Included
- Responsive homepage inspired by modern exam-preparation platforms (original Rishabh Classes branding and layout).
- Sign-up and login gate before students can attempt tests.
- Student dashboard with unfinished tests and recent results.
- Two SSC CGL Tier-I mock papers with 100 questions each.
- Timed MCQ interface, question palette, previous/next, clear response, submit confirmation, score and answer review.
- Autosaves selected answers, current question, and remaining timer so the student can resume later on the same browser/device.

## Important prototype limitation
This is a front-end demo, not production authentication. User records and passwords are stored in browser `localStorage`, so they are not secure and do not sync between devices or browsers. Do not use real or reused passwords. For a public launch with secure sign-up/login and student data saved across devices, connect a backend such as Supabase or Firebase, use server-side authentication and database access rules, and move scoring/answer keys to the server.

## Content note
The existing `questions.json` question bank is preserved. Review question wording and answer keys before using these papers for a real exam.
