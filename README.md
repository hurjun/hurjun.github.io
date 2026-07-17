# hurjun.github.io

Personal portfolio website for Jun Hur (허준) — a software engineer with 5+ years building production systems across robotics, fintech, and healthcare, focused on the reliability of cyber-physical systems: cross-layer fault diagnosis, failure prediction from operational telemetry, and simulation-based validation before deployment. The site is written in English for a US graduate-admissions audience and mirrors the narrative of the statement of purpose. Dark theme only, with a light palette applied when printing.

🔗 **Live site:** [hurjun.github.io](https://hurjun.github.io)

## Overview

A single-page portfolio built with vanilla HTML, CSS, and JavaScript. No frameworks or build tools required — just push and it deploys via GitHub Pages.

## Sections

- **Research Interests** — three research questions (cross-layer fault diagnosis, failure prediction from telemetry, simulation-based pre-deployment validation), each rooted in an operated system
- **About** — the power-plant patrol failure story, the deterministic-software thesis, and the graduate-study goal
- **Skills** — languages, frameworks, cloud, databases, tools
- **Experience** — work history with tech stacks, including the operational incidents behind each research question
- **Projects** — 8 project cards with full-screen detail overlay, screenshots, and links, plus a **Selected Open-Source Projects** list linking the strongest GitHub repos (`github.com/hurjun`)
- **Education** — degree (with full-time-work context) and the 2017 KIISE Grand Prize (Reacord)

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
