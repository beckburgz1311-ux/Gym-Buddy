# CodeTrail

A mobile-first, installable coding-learning app inspired by the clarity and momentum of language-learning apps, with original branding and interface design.

## Current course

The first playable course teaches beginner Python through nine bite-sized lessons:

- Printing and basic syntax
- Variables
- Numbers and strings
- Boolean comparisons
- If statements
- Logical operators
- Loops
- Functions
- A final mixed challenge

## Features

- A visual learning path with locked, current and completed lessons
- Multiple-choice, fill-the-blank and code-writing challenges
- Instant explanations after every answer
- XP, hearts, daily goals and learning streaks
- Practice mode that restores hearts
- Achievements and a progress profile
- Local browser saves with no account or database
- Installable PWA with offline support
- Responsive mobile and desktop design

## Run locally

Open `index.html` directly, or serve the repository with a static web server:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## GitHub Pages

When GitHub Pages is enabled for the branch/root being deployed, the app can run as a static site with no build step.

## Technical notes

The app is dependency-free and contained in `index.html`, with `manifest.webmanifest`, `icon.svg` and `sw.js` providing installability and offline support. User progress is stored in `localStorage` under `codetrail-progress-v1`.
