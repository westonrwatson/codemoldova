# CodeMoldova 2025

A free, hands-on programming course running May–July 2025 in Moldova. Open to everyone — no experience needed.

## What this repo is

This is the course website: a single `index.html` file that students can visit to see the weekly roadmap, click into each session, and find links and resources. It's deployed on Vercel and auto-updates whenever this file changes.

## Course structure

8 weeks · 3 sessions per week · 1 hour each

| Day | Focus |
|---|---|
| Monday | Teach & Learn — new concepts, live demos |
| Wednesday | AI Exploration — play with AI tools, understand what they can and can't do |
| Thursday | Build Together — hands-on project work |

### Phases

- **Phase 1 (Weeks 1–2)** — Foundations: Python basics, terminal, logic & loops
- **Phase 2 (Weeks 3–4)** — Python Projects: data structures, APIs, AI-powered scripts
- **Phase 3 (Weeks 5–6)** — Web Development: HTML, CSS, JavaScript, GitHub, Vercel
- **Phase 4 (Weeks 7–8)** — Final Project: demo day, deployment, portfolios

## How to update the site

### Add an announcement or resource

Edit the `announcements-grid` section near the bottom of `index.html`. Copy an existing card block and change the text:

```html
<div class="announcement-card">
  <div class="ann-date">Week 3</div>
  <div class="ann-tag">Resource</div>
  <div class="ann-title">Your title here</div>
  <div class="ann-body">A short description of what this is.</div>
  <a class="ann-link" href="https://..." target="_blank">Link text →</a>
</div>
```

Tag options: default (green), `tool` (yellow), `reading` (purple)

### Update session content

Each week's content lives in the `phases` array in the `<script>` section of `index.html`. Find the week and day you want to edit and update the `title`, `desc`, `points`, or `resources` fields.

### Deploy changes

Just commit and push to this repo — Vercel redeploys automatically within ~60 seconds.

## Tools students will use

- Python 3.12 — [python.org/downloads](https://www.python.org/downloads/)
- VS Code — [code.visualstudio.com](https://code.visualstudio.com/)
- GitHub — [github.com](https://github.com)
- Vercel — [vercel.com](https://vercel.com)
- Figma — [figma.com](https://figma.com)
- Claude — [claude.ai](https://claude.ai)

## About

This course is organized as a nonprofit initiative. Students find us through Facebook. It's free, always has been, and always will be.
