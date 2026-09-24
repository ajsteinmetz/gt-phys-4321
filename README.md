# gt-phys-4321

PHYS 4321/4322 &mdash; Advanced Laboratory I/II

This repository contains course materials for PHYS 4321/4322 (Advanced Laboratory I/II), a 3-credit laboratory course offered at the School of Physics, Georgia Institute of Technology. Materials include the syllabus, welcome page, list of experiments, supplemental guides, and lecture slides.

The site is built with [Quarto](https://quarto.org/). Project configuration is in `_quarto.yml`; visual styling is in `gatech-theme.css`. It is intended to be hosted at **ajsteinmetz.github.io/gt-phys-4321** via GitHub Pages.

## Contents

- `course-files/` &mdash; `syllabus.qmd`, `ai-disclosure-statement.qmd`
- `labs/` &mdash; list of available experiments
- `supplemental/` &mdash; `technical-writing.qmd`, `notebook-guidelines.qmd`, `error-analysis.qmd`
- `lectures/` &mdash; RevealJS slides (`lab-guidelines.qmd`, `lab-report.qmd`) and lecture index

## Local Development

Requires [Quarto](https://quarto.org/docs/get-started/) 1.4 or later.

```bash
quarto render    # build to _site/
quarto preview   # live-reload preview
```

## Publishing

```bash
quarto publish gh-pages
```

The `gh-pages` branch contains only rendered output and should not be edited directly.

## Semester Rollover

Tag the repository (e.g. `git tag fall-2026`), then update the semester, CRNs, meeting time, room, and schedule dates in `index.qmd` and `course-files/syllabus.qmd`.
