# hurjun.github.io

Personal portfolio website for Jun Hur (허준) — a software engineer with 6+ years across robotics, fintech, and healthcare, focused on autonomous-robot fleet operations, multi-robot path planning, and sim-to-real. The site content is written in English, emphasizing reliable, well-engineered software in safety-critical environments.

🔗 **Live site:** [hurjun.github.io](https://hurjun.github.io)

## Overview

A single-page portfolio built with vanilla HTML, CSS, and JavaScript. No frameworks or build tools required — just push and it deploys via GitHub Pages.

## Sections

- **Interests** — field automation, multi-robot coordination, sim-to-real, digital twins, real-time monitoring
- **About** — background and key highlights
- **Skills** — languages, frameworks, cloud, databases, tools
- **Experience** — work history with tech stacks
- **Projects** — 8 project cards with full-screen detail overlay, screenshots, and links, plus a **Selected Open-Source Projects** list linking the strongest GitHub repos (`github.com/hurjun`)
- **Education** — degree and certification

## Local Development

No build step. Open `index.html` directly, or serve the folder:

```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Project Detail Pages

Clicking any project card opens a full-screen overlay with:
- Screenshot gallery
- Full description
- Key features
- Tech stack
- Link to live site (where available)

## Adding / Updating Screenshots

All images live in the `asset/` folder. Filenames must be **ASCII only** (no spaces, no Korean characters).

| Project | Image files |
|---|---|
| Robot Fleet Management System | `asset/gole-fms-01.png` … `asset/gole-fms-15.png` |
| CRISK | `asset/crisk.png`, `asset/crisk-chatbot.png` |
| Credit Imbalance Tracker | `asset/credit-imbalance.png` |
| Credivalue | `asset/credivalue.png` |
| Robot Control System | `asset/robot-hyundai.jpeg`, `asset/robot-seoyeon.jpeg`, `asset/robot-gseps.png` |
| Service Robot Display | `asset/robot-skhynix.jpeg`, `asset/robot-518.jpeg` |
| Profile photo | `asset/face.jpeg` |

## Commit Convention

This project follows [Conventional Commits](https://www.conventionalcommits.org/):

```
feat(section): add new feature
fix(section): correct a bug or wrong content
style(section): visual changes only
content(section): text or data update
chore: file moves, renames, cleanup
```
