# Work Comp · Field Guide

An interactive English learning edition of the Illinois Workers’ Compensation Commission’s 2013 *Handbook on Workers’ Compensation and Occupational Diseases*. All 94 questions across 11 sections have a lesson, original PDF page reference, and link to the 2024 official revision. The site shows one question at a time and stores progress in the local browser.

## Learning features

- Search, sequential reading, completion tracking, and text-size control.
- A three-step micro demonstration for each question; chapter labs cover notice, CompFile, provider choice, TTD/TPD calculations, four PPD paths, and the full scheduled body-part lookup.
- Three named court cases with facts and outcomes: Bryon Kawa, Jeff Urban, and Craig Kolin. Each links to the official Illinois court opinion.
- Responsive mobile layout and reduced-motion support.

## Sources and date

- The user-supplied PDF has the same SHA-256 hash as the [official IWCC 2013 PDF](https://iwcc.illinois.gov/content/dam/soi/en/web/iwcc/about/handbook/documents/handbook.pdf).
- The [IWCC handbook page](https://iwcc.illinois.gov/about/handbook.html) listed the June 6, 2024 revision when checked on September 28, 2026. Each lesson links to the matching PDF page.
- The 2013 paper-filing instructions have been replaced by CompFile. Historical links, amounts, and procedures should not be acted on without checking current materials.
- Case summaries derive from Illinois court opinions. Ordinary interactive examples are educational illustrations, not actual adjudications.

This is a learning aid. Actual claims depend on current law, injury date, and facts. Calculators demonstrate formulas without statutory minimums or maximums.

## Run and publish

```bash
npm ci
npm run dev
npm run build
```

Pushing to `main` builds and deploys via `.github/workflows/pages.yml`. No API key or backend is needed. GPT API spend is $0. The independent Chinese repository is [iwcc-handbook-zh](https://github.com/GMyoung/iwcc-handbook-zh).
