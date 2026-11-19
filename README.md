# CISC7204 Assignment 02 — Revised Pair Project Proposal

This repository presents my Assignment 02 portfolio work for **CISC7204 Data Science and Data Visualization** at the University of Macau.

## Coursework scope

Assignment 02 required a **revised pair project proposal** rather than a separate code submission. This repository therefore preserves the submitted proposal and summarizes its planned evidence, methods, deliverables, and collaboration structure. It does not present later analysis files as if they had been submitted for Assignment 02.

## Project overview

**Title:** Monthly Visitor Arrivals and Hotel Room Occupancy in Macao, 2024–2025  
**Region:** Macao SAR  
**Domain:** Tourism and hospitality

The proposal asks:

> Is there a statistically significant positive association between monthly visitor arrivals and the average hotel room occupancy rate in Macao from January 2024 to December 2025? Do months with more arrivals tend to have higher occupancy?

It develops the preliminary Assignment 01 idea into a structured four-stage plan covering data acquisition, validation, cleaning, analysis, visualization, interpretation, reproducibility, and peer review.

## Proposed data

The project uses two public monthly datasets from the [Statistics and Census Service (DSEC), Macao SAR Government](https://www.dsec.gov.mo/):

- [Visitor Arrivals time-series database](https://www.dsec.gov.mo/timeseriesdatabase.aspx?keyindicatorid=27&lang=en-US) — total monthly visitor arrivals (persons).
- [Hotel Occupancy time-series database](https://www.dsec.gov.mo/timeseriesdatabase.aspx?keyindicatorid=9&lang=en-US) — monthly average room occupancy rate (%).

The proposed analysis period is January 2024 through December 2025, giving 24 aligned monthly observations.

## Proposed workflow

1. Preserve the official source files and document links, dates, definitions, units, coverage, and revision notes.
2. Standardize month labels, filter the shared period, merge one-to-one by month, and check missing, duplicate, and out-of-range values.
3. Report descriptive statistics and Pearson correlation, compare month-to-month changes as a sensitivity check, and create two complementary visualizations.
4. Explain seasonality, time dependence, anomalous months, and the distinction between association and causation; then reproduce and cross-review the work.

## Proposed visualizations

- Two vertically aligned line charts with a shared time axis, using separate scales for arrivals and occupancy.
- A scatterplot of visitor arrivals against occupancy, colored by year, with an overall fitted line.

The two views are complementary: the time series shows when movements occur, while the scatterplot shows the overall direction, spread, and exceptions in the relationship.

## Repository contents

```text
.
├── README.md
├── CISC7204-Assgn02-Pair09-RevisedProjectProposal.docx
└── CISC7204-Assgn02-Pair09-RevisedProjectProposal.pdf
```

The Word document is the submitted editable proposal. The PDF copy is included for convenient in-browser review.

## Authorship and collaboration

The proposal is pair work by **CHEN RUXIN** and **XIE ZIQI**.

- Chen Ruxin: project coordinator and liaison; source log and requirement checklist; report and document integration; instructor clarifications.
- Xie Ziqi: data analysis lead and progress tracker; master dataset and notebook; validation, statistical analysis, and milestone tracking.
- Both members: shared meeting records, finalized the research question and visual plan, peer-reviewed each other's primary work, and approved the submission.

This portfolio repository is published under Chen Ruxin's GitHub account to document the coursework accurately; it does not claim sole authorship of collaborative work.

## Relationship to Assignment 01

Assignment 01 contains the preliminary proposal and the reproducible analysis materials for the same topic. It is maintained as a separate repository so that each bonus-work URL maps clearly to the corresponding coursework item.
