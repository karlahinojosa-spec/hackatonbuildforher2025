# hackatonbuildforher2025 — Mentor Micro-Coach (Women in Tech)

## Problem
First-time hackers struggle to scope, plan, and pitch a project within 24 hours.

## User
Women in Tech hackathon participants who need structure and speed to go from idea → plan → pitch.

## Success
From a short brief, generate a 1-page plan + 5-slide pitch outline in **< 3 minutes**, with **≥80% helpfulness rating** in a quick 1–5 survey.

## Solution (MVP)
- Simple form: **goal, audience, problem, metric of success, constraints**.
- Generator returns a **1-page action plan** (problem, user, scope, risks, metrics, timeline).
- Auto-create **5-slide pitch outline** (titles + bullet copy + speaker notes).
- **Download** as `.md` (always) and `.pptx` (stub if library not wired).

## How it works
- **web/**: React form → shows plan + slides, buttons to copy/download.
- **api/**: minimal endpoint that calls the LLM and formats outputs.
- **data/**: prompt templates + example briefs.
- **docs/**: prompt policy & demo script.
- **scripts/**: export helpers (md/pptx stub).

## Run (placeholder; we’ll complete during hack)
- Front: `npm run d
