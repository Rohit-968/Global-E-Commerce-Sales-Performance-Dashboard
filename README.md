# Global E-Commerce Sales Performance Dashboard

**Interactive Excel BI dashboard analyzing revenue, profitability, and regional performance across a global e-commerce dataset — built for executive reporting and strategic decision-making.**

[![Excel](https://img.shields.io/badge/Microsoft-Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)](https://microsoft.com/excel)
[![BI](https://img.shields.io/badge/Type-Business%20Intelligence-0078D4?style=flat-square)]()
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

---

## Key findings

- **North America and Europe** account for the largest revenue share — strong penetration in developed markets with room to optimize margin, not volume
- **Electronics and Furniture** lead in both revenue and profitability; lower-margin categories signal pricing or supply chain inefficiencies worth addressing
- **Corporate customers** carry higher average order values than individual segments — a case for differentiated account strategy
- **Q4 drives disproportionate sales peaks** — inventory and campaign planning should front-load for holiday-season demand
- **Several high-volume regions operate at compressed margins** — geographic profitability analysis points to actionable cost or pricing levers

---

## Dashboard preview

![Dashboard Overview](https://github.com/user-attachments/assets/be1731c0-c9b5-4456-a0aa-2f6fbaff267c)
![KPI Summary](https://github.com/user-attachments/assets/a16fb658-c98e-4ca3-a3ed-1c761623146c)

---

## What the dashboard tracks

| KPI | Purpose |
|---|---|
| Total revenue | Top-line performance across all regions and segments |
| Total quantity sold | Volume trends by product and category |
| Profit margin % | Profitability health — not just revenue |
| Regional sales distribution | Geographic concentration and expansion signals |
| Top products & categories | SKU-level performance for inventory prioritization |
| Customer segment contribution | Corporate vs. individual revenue split |
| Month-over-month growth | Momentum and seasonality detection |

---

## How it's built

**Data preparation**
Raw data cleaned and transformed using Excel filters, text-to-columns, IF statements, and date-based calculations. Inconsistencies resolved before any aggregation.

**Analysis layer**
Pivot Tables for dynamic aggregation across region, category, segment, and time. Advanced formulas — `INDEX-MATCH`, `SUMIFS`, `IFERROR` — for cross-sheet KPI computation.

**Dashboard layer**
Slicers and interactive filters for executive drill-down. Conditional formatting for instant trend identification. Custom combo, column, line, and pie charts for KPI storytelling.

---

## Tech stack

`Microsoft Excel` `Pivot Tables` `INDEX-MATCH` `SUMIFS` `Conditional Formatting` `Slicers` `Custom Charts`

---

## Business impact

The findings directly support three decisions:

1. **Market prioritization** — identify which regions to defend vs. grow vs. fix
2. **Inventory optimization** — align stock planning with Q4 demand curves and top-category performance
3. **Margin improvement** — flag high-volume, low-margin regions for pricing or supply chain review

---

## Roadmap

- [ ] Power Query integration for automated data refresh and transformation
- [ ] Power BI version for richer interactivity, DAX measures, and scalable distribution

---

## License

MIT — see [LICENSE](LICENSE) for details.
