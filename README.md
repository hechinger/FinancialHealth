# College Financial Health Tracker

The Hechinger Report's interactive tracker of financial distress at
U.S. four-year colleges: closures, layoffs, program cuts, accreditation
actions, and research-funding losses.

**Live site:** https://financialtracker.hechingerreport.org/

## What's in this repository

- The static site itself: `index.html`, `school.html`, `cuts.html`,
  `accreditation.html`, `research.html`, `methodology.html`,
  `styles.css`, `js/`, `assets/`
- `data/` - the JSON and CSV exports the site reads, updated
  automatically by The Hechinger Report's data pipeline
- `scripts/` and `tests/` - the pipeline and test code, published for
  transparency

The pipeline's working files (scraper caches, review queues, editorial
override records, and other derived CSVs) live in a private source
repository; this repository receives the finished public data.

## Rights

- **Data** (`data/` and the site's CSV downloads): reusable with
  attribution under CC BY 4.0 - see [LICENSE-DATA.md](LICENSE-DATA.md)
- **Code**: all rights reserved; published for transparency - see
  [LICENSE-CODE.md](LICENSE-CODE.md)
- **Branding and assets**: all rights reserved - see
  [LICENSE-ASSETS.md](LICENSE-ASSETS.md)

## Methodology and corrections

How the data is collected and what the fields mean:
https://financialtracker.hechingerreport.org/methodology.html

Corrections and questions: https://hechingerreport.org/contact/
