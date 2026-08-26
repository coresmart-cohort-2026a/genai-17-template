<!--
  Complete this before you submit. The reviewer reads it first.
  Paste the LINK TO THIS PULL REQUEST into the Submit item on the LMS.
-->

## Which project is this?

- **Week:** <!-- e.g. 1 -->
- **Project folder:** <!-- e.g. project-02-minutemaker -->

## What I built

<!-- Three or four sentences in your own words. What it does, and how. -->

## How to run it

```bash
# commands a reviewer can paste on a clean machine
```

## Design decisions

<!-- The interesting part. What did you choose, and what did you rule out?
     Prompt structure, model choice, chunking, retries, error handling. -->

## Known limitations

<!-- What does not work, or works badly. Being straight about this scores better
     than pretending it is finished. -->

---

## Checklist

Tick every box. An unticked box is a question your reviewer will ask.

### Secrets
- [ ] No API key, token, or password appears anywhere in this diff
- [ ] `.env` is **not** committed — `git ls-files | grep -c "^\.env$"` returns `0`
- [ ] Any example config is `.env.example`, with placeholder values only

### The Week 1 data
- [ ] `project-02-minutemaker/data/` is **unmodified** — five transcripts and
      `example-output.json`, exactly as they arrived
- [ ] My code handles `transcript-04.txt`, which is **intentionally blank** —
      the empty-input case — without crashing

### Code
- [ ] It runs from a clean clone by following "How to run it" above
- [ ] Output for `transcript-01.txt` is compared against `example-output.json`
- [ ] No absolute paths from my own machine (`/Users/...`, `C:\...`)
- [ ] No large binaries, datasets, or `.venv/` committed

### This pull request
- [ ] Branched off `main`, and targets `main`
- [ ] Title says which week and project this is
- [ ] I have read my own diff, file by file, before requesting review

### Submission
- [ ] I am pasting **this pull request's link** into the LMS Submit item —
      not the repository link, not the branch link, not the commit link
