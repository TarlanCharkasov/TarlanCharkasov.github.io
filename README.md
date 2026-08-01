# tarlancharkasov.github.io

Personal site for **Tarlan Charkasov, ACCA** — IFRS management accounts, budgeting and
forecasting, financial modelling, and reporting automation.

Live at: https://tarlancharkasov.github.io

## Contents

| Path | What it is |
|------|------------|
| `index.html` | The entire site. One file, no build step, no dependencies. |
| `samples/danube-management-pack.xlsx` | Full 12-tab IFRS management pack (Excel) |
| `samples/danube-management-pack.pdf` | The same pack as a 23-page PDF |
| `samples/variance-summary.pdf` | 3-page actual-vs-budget summary |

## About the work samples

The samples are built on **Danube Consumer Health Kft**, a fictional consumer-health
distributor. All figures are synthetic and were generated for portfolio purposes.
No client or employer data is used anywhere in this repository.

The pack is driven entirely from two trial balances (actual and budget). The P&L,
balance sheet, cash flow and KPI tabs contain no hardcoded figures — every line is a
`SUMIFS` against the trial balance, routed through a single mapping column on the
Chart of Accounts tab. A Checks tab holds ten integrity controls covering double entry,
the balance sheet identity, the cash flow reconciliation and equity roll-forward.

## Editing the site

Edit `index.html` directly on GitHub (click the file, then the pencil icon) or upload a
replacement. Changes go live within about a minute.

Placeholders to replace before sharing widely:

- `YOUR-LINKEDIN-HANDLE`
- `YOUR-FIVERR-USERNAME`
- `YOUR-UPWORK-ID`
