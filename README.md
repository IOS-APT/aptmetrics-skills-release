# APTMetrics Skills — Release

Approved Claude Desktop skills for general use across APTMetrics. Everything here has already gone through review in the (restricted) `aptmetrics-skills-review` repo — see that repo if you want to propose a new skill or change an existing one.

**Don't edit skill content directly in this repo.** Changes go through `aptmetrics-skills-review` and arrive here via `promote.sh`, so there's always a reviewed, merged PR behind anything that ends up here.

## Using a skill from this repo

Pick whichever fits how you work:

- **Clone/pull the repo** and point your Claude Desktop skills folder at `skills/<skill-name>/`.
- **Package a single skill as a `.skill` file** (zip the `skills/<skill-name>/` folder with a `.skill` extension) and share it — Claude Desktop shows a "Save skill" install button for `.skill` files.

## What's here

See `skills/` for the current list, and `PROMOTIONS.md` for the history of what was promoted, when, and by whom.

## Repo layout

```
aptmetrics-skills-release/
  README.md
  PROMOTIONS.md      # append-only log of promotions from aptmetrics-skills-review
  skills/
    <skill-name>/
      SKILL.md
      ...
```
