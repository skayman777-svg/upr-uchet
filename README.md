# Management Accounting Workbook — Workbench-12

An Excel / Google Sheets workbook for a small manufacturing business (a fictional joinery workshop): transactions
go on one sheet, while the monthly summary and the dashboard are calculated with formulas.

**Live demo:** https://skayman777-svg.github.io/upr-uchet/ (interactive copy of the four sheets)

**File:** `workbench12-management-accounting.xlsx`

## Sheets

- **Transactions** — 400 transactions for 2025; category, product line and account are picked from dropdowns,
  type and month are filled in by formulas.
- **Monthly summary** — income and expenses by category and month (SUMIFS), variable costs, contribution margin,
  net profit, profit margin, cash at month end, revenue by product line, data check.
- **Dashboard** — yearly KPIs and four charts: income vs expenses, net profit and cash, revenue by product line,
  expense breakdown.
- **Lookups** — categories with type and group, product lines, accounts with opening balances.

## Notes

- Standard functions only (SUMIFS, VLOOKUP, INDEX/MATCH), no macros; recalculated in LibreOffice with 0 formula errors.
- Cash-basis accounting: the balance is derived from profit, without loans, debts or transfers between accounts.
- All data is fictional.
