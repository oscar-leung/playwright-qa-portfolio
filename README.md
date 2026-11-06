# playwright-qa-portfolio (merged)

**This suite now lives in [`qa-portfolio/playwright`](https://github.com/oscar-leung/qa-portfolio/tree/main/playwright).** It was merged there in September 2026 so the Selenium + pytest and Playwright + TypeScript suites run side by side against the same application, in one CI pipeline with one nightly report.

Go there for the current code, the CI status and the published reports:

- Repo: https://github.com/oscar-leung/qa-portfolio
- Nightly reports: https://oscar-leung.github.io/qa-portfolio/
- Case studies: https://github.com/oscar-leung/qa-portfolio/tree/main/case-studies

This repository is kept read-only for history. The code here is the pre-merge snapshot: Playwright + TypeScript, Page Object Model, storageState auth reuse, UI tests against Sauce Demo and API tests against jsonplaceholder, with a `test.fail()`-pinned known defect. `STUDY_GUIDE.md` is still useful as notes on why the suite is structured the way it is.
