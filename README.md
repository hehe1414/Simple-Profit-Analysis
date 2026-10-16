# Simple Profit Analysis – Superstore

**Task 16 – Simple Profit Analysis**
Veda Technology | Data Analytics Track | Level 1, Day 16

## About
I compared total and average profit across the three product categories of the Sample Superstore dataset (2014-2017, 9,994 transactions) using Excel formulas and charts. The goal was to understand basic profitability, not just sales.

## Profit summary
| Category | Total Profit | Avg Profit per Transaction | Transactions | Total Sales | Profit Margin |
|----------|-------------|----------------------------|--------------|-------------|---------------|
| Furniture | 18,451 | 8.70 | 2,121 | 741,999 | 2.5% |
| Office Supplies | 122,491 | 20.33 | 6,026 | 719,047 | 17.0% |
| Technology | 145,455 | 78.75 | 1,847 | 836,154 | 17.4% |
| **Total** | **286,397** | **28.66** | **9,994** | **2,297,201** | **12.5%** |

## Charts
1. Total Profit by Category (column chart)
2. Average Profit per Transaction by Category (column chart)

## Findings
- **Technology** earns the most in total (145,455) and the most per transaction (78.75), with the highest margin (17.4%)
- **Office Supplies** is second in total profit (122,491), but earns only 20.33 per transaction because it has many small transactions (6,026)
- **Furniture** has higher sales than Office Supplies (742K vs 719K), but earns the least profit: 18,451 in total, 8.70 per transaction and a margin of only 2.5%

**Takeaway:** high sales do not always mean high profit. Furniture sells a lot but keeps very little of it.

## How I checked my numbers
The category totals add up to the grand total (286,397), and this matches the sum of the Profit column on the Raw Data tab shown in Excel's status bar.

## Files
- `Simple_Profit_Analysis.xlsx` – workbook with the Raw Data tab and the Profit Summary tab (formulas and charts)
- `profit_summary_screenshot.png` – screenshot of the Profit Summary tab
- `README.md`

## Tools used
Microsoft Excel (SUMIFS, COUNTIFS, AVERAGEIFS, charts)

## Author
Rabia
