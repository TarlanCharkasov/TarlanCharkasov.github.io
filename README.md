# tarlancharkasov.github.io

Personal site for **Tarlan Charkasov, ACCA** — IFRS management accounts, budgeting and
forecasting, financial modelling, and reporting automation.

Live at: https://tarlancharkasov.github.io

## Contents

```
index.html                 The entire site. One file, no build step, no dependencies.
samples/
  danube/                  Danube Consumer Health Kft. — IFRS reporting
    danube-management-pack.xlsx        12-tab monthly pack, 2,146 formulas, 10/10 checks
    danube-management-pack.pdf
    variance-summary.pdf               3-page actual vs budget summary
  kestrel/                 Kestrel Nutrition Kft. — planning & analysis
    monthly-management-accounts.xlsx   7 tabs, 468 formulas, board pack with actions
    monthly-management-accounts.pdf
    three-statement-model.xlsx         FY2024A–FY2030E, 763 formulas, 3 scenarios
    three-statement-model.pdf
    commercial-dashboard.html          self-contained, opens in any browser
    commercial-dashboard.png
  halcyon/                 Halcyon Metalworks Kft. — cash, automation & capex
    13-week-cash-flow-forecast.xlsx    8 tabs, RCF sweep, covenant test, 16/16 checks
    13-week-cash-flow-forecast.pdf
    cost-centre-tool-automated.xlsx    the automated month-end tool
    cost-centre-tool-manual-before.xlsx  the manual routine it replaced
    vba-source-modules.bas             811 lines, six modules
    cost-centre-automation.pdf
    capital-investment-appraisal.xlsx  NPV / IRR / MIRR, 12 scenario runs
    capital-investment-appraisal.pdf
```

## About the work samples

**Danube Consumer Health Kft.**, **Kestrel Nutrition Kft.** and **Halcyon Metalworks Kft.**
are fictional companies. All figures are synthetic and were generated for portfolio
purposes. No client or employer data is used anywhere in this repository.

Every workbook carries its own integrity checks, and none is presented as complete until
they all pass: 10 of 10 for Danube, 16 of 16 for each Halcyon deliverable, and a four-way
check panel across seven years in the Kestrel model.

The Kestrel model is worth opening on the Assumptions tab: switching cell `C5` to 3
(downside) flexes all seven years and correctly raises a covenant breach flag at 2.35x
against the 2.25x limit, while the balance sheet still balances in every year.

## Editing the site

Edit `index.html` directly on GitHub (click the file, then the pencil icon) or upload a
replacement. Changes go live within about a minute.

Placeholders to replace before sharing widely:

- `YOUR-LINKEDIN-HANDLE`
- `YOUR-FIVERR-USERNAME`
- `YOUR-UPWORK-ID`
