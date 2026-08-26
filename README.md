# <!-- your name --> — Applied GenAI & Agentic AI Engineering

CoreSmart.AI · 17-Week Applied GenAI & Agentic AI Engineering Program · Cohort 2026A

This repository holds all sixteen graded projects for the programme. One
repository, one project folder per build, from Week 1 through to December.

> Fill in the sections below as you go. The headings are here so that by Demo Day
> this reads as a body of work rather than a folder of exercises.

---

## About me

<!-- Two or three lines. Who you are, what you did before this, what you want to
     build. This is the first thing an employer reads. -->

- **GitHub:** <!-- your username -->
- **Focus:** <!-- e.g. agentic systems, RAG, evaluation -->

---

## Projects

| # | Week | Project | Status | Notes |
|---|------|---------|--------|-------|
| 01 | 1 | ReleaseBot (guided lab) | — | practice only, not submitted |
| 02 | 1 | MinuteMaker | Not started | <!-- one line when done --> |
| 03 | 2 | <!-- --> | | |

<!-- Add a row each week. Keep Status to one of: Not started, In progress,
     Submitted, Reviewed. -->

---

## Setup

How to run anything in this repository on a clean machine.

```bash
# 1. clone
git clone https://github.com/coresmart-cohort-2026a/<your-username>-genai-17.git
cd <your-username>-genai-17

# 2. environment
python3 -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate

# 3. per-project dependencies
#    You create requirements.txt yourself as you build. ReleaseBot's copy in
#    coresmartai/labs (week-01/releasebot/requirements.txt) is a good starting point.
cd project-02-minutemaker
pip install -r requirements.txt

# 4. your API key
#    Copy .env.example from coresmartai/labs week-01/releasebot/, rename to .env,
#    and put your own key in it. .env is already git-ignored.
```

### The .env rule

Your API key lives in `.env`. That file is listed in `.gitignore` and **must
never be committed**. If you ever think a key has been committed, rotate it
immediately and tell the team — do not try to erase it from history first.

---

## How work is submitted

Every graded project follows the same rhythm:

1. Branch off `main` — `git switch -c week-01-minutemaker`
2. Build inside that week's project folder
3. Commit and push
4. Open a pull request into `main`
5. Paste the **pull request link** into the Submit item on the LMS

The pull-request checklist in `.github/pull_request_template.md` fills itself in
when you open a PR. Complete it before you submit.

---

## Repository layout

```
.
├── project-01-releasebot/        guided lab — practice, not submitted
├── project-02-minutemaker/       Week 1 graded build — your code goes here
│   └── data/                     test transcripts + example output — DO NOT EDIT
├── .github/                      pull-request checklist
├── .gitignore                    already protects .env
└── README.md                     this file
```

Add a new `project-NN-name/` folder per week. Do not restructure what is here —
your reviewer and the Week 1 brief both rely on these paths.

---

## Reflections

<!-- Optional but worth doing. A few lines each week on what was hard and what
     you would do differently. By December this is the most interesting part of
     the repository. -->

---

*Private during the cohort. This repository stays yours afterwards.*
