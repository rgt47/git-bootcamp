# Git and GitHub for Biostatistics: A One-Week Boot Camp
*2026-07-25 17:29 PDT*

A short preparatory course for incoming graduate students in
biostatistics and adjacent programmes who arrive with no or
minimal version-control experience. Five days, one chapter
each.

## Structure

- **Day 1** Why Version Control, Setup, First Repository
- **Day 2** Recording History: Commits, Diffs, Undoing
- **Day 3** Branching and Merging
- **Day 4** GitHub: Remotes and Publishing (with `gh`)
- **Day 5** Collaboration and Reproducible Research

Each day is approximately 1 hour of lecture content + 2
hours of homework with worked solutions. No examinations.

## Build

```bash
quarto render
```

The cover is generated procedurally:

```bash
Rscript images/build-cover.R
```

## Position in the series

This boot camp is the version-control half of the two-part
pre-program preparation. Its companion is *R for
Biostatistics: A One-Week Boot Camp*. After both, the four
follow-on volumes pick up where the boot camps leave off:

- *Biostatistics Practicum* — workflow infrastructure (Git
  in depth, Docker, renv, Quarto, CDISC)
- *Statistical Computing in the Age of AI* — methods and
  computing
- *Advanced Statistical Computing in the Age of AI* —
  advanced computing
- *Applied Generative AI for Public Health and
  Biostatistics* — generative AI

A sixth volume, *Applied Statistical Methods for Public
Health*, covers the applied methodological core (causal
inference, longitudinal, survival applied, clinical trials,
missing data, meta-analysis).

## License

Prose: CC BY-NC-ND 4.0. Code: CC0 1.0.
