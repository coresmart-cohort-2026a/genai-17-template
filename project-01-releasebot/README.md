# Project 01 — ReleaseBot (guided lab)

This is the **practice** lab for Week 1. Nothing is submitted from this folder.

You do not build ReleaseBot from scratch. The complete reference implementation —
the FastAPI service, its LLM client, the tests, and two notebooks — lives in the
public CoreSmart labs repository:

**https://github.com/coresmartai/labs**

Specifically:

- Lab code and notebooks — `week-01/releasebot/`
- Colab walk-through — `week-01/releasebot/releasebot_colab.ipynb`
- Endpoint-by-endpoint exercises — `week-01/releasebot/week1_notebook.ipynb`

## What to do

1. Open the notebooks above in Google Colab straight from GitHub, and run them.
2. Read `week-01/releasebot/app/` until you can say what each module does.
3. Copy anything useful into `../project-02-minutemaker/` when you build the
   graded project. Re-pointing ReleaseBot's `app/` is the intended route — there
   is deliberately no starter app code in project-02.

## Notes

- `labs` is **public on purpose**, so no secret may ever be committed there or
  here. Your API key belongs in `.env`, which is already git-ignored.
- Copy `.env.example` from `week-01/releasebot/`, rename it to `.env`, and put
  your own key in it.
- Do not fork `coresmartai/labs` to do your work. Your graded work lives in this
  repository.

You can add your own scratch files in this folder. They are not marked.
