# DSA-Prep
# Apex DSA — Amazon SDE Interview Prep

A single-file, offline-first web app for preparing for Amazon SDE / online-assessment (OA) interviews. Everything — UI, styling, logic, and your progress data — lives in one self-contained `apex-dsa.html` file. No build step, no server, no dependencies to install.

## Features

- **Amazon OA Preparation** — most-tested topics and a prep checklist tailored to Amazon assessments.
- **Top Amazon DSA Patterns** — the recurring problem patterns worth drilling.
- **Question Bank** — browse problems by topic and difficulty.
- **Daily Practice Tracker** — log your daily reps and keep a streak going.
- **Timed Practice Mode** — run focused, time-boxed drills.
- **Mock Interview Mode** — simulate an interview and rate how it went.
- **Weak Topic Detector** — surfaces the areas you keep struggling with.
- **Confidence Score** — a rolled-up measure of how interview-ready you are.
- **Revision Heatmap** — a last-14-days view of your activity.
- **Dashboard** — your interview "command center" tying it all together.

## Getting Started

Just open the file in any modern browser — that's it.

- **Double-click** `apex-dsa.html`, or
- Drag it into a browser window, or
- From a terminal:
  - Windows: `start apex-dsa.html`
  - macOS: `open apex-dsa.html`
  - Linux: `xdg-open apex-dsa.html`

### Optional: serve it locally

If you prefer an `http://` origin (some browsers restrict certain APIs on `file://`):

```bash
python -m http.server 8000
# then visit http://localhost:8000/apex-dsa.html
```

## Data & Privacy

Your progress (tracker, scores, logs) is stored in your browser's **localStorage**. It never leaves your machine and is not sent anywhere. Note:

- Data is per-browser and per-origin — opening the file in a different browser, profile, or via a different path starts fresh.
- Clearing browser data will reset your progress.

## Requirements

- Any modern browser (Chrome, Edge, Firefox, Safari).
- An internet connection is only needed for web fonts (Google Fonts); the app works offline without them.

## Tech

Plain HTML, CSS, and vanilla JavaScript in a single file — no frameworks, no bundler.
