<div align="center">

# Global E-Commerce Sales Performance Dashboard

### Executive-grade Business Intelligence built entirely in Microsoft Excel —
### transforming raw transactional data into boardroom-ready strategy.

[![Excel](https://img.shields.io/badge/Microsoft-Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)](https://microsoft.com/excel)
[![Type](https://img.shields.io/badge/Type-Business%20Intelligence-0078D4?style=flat-square)]()
[![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)]()
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

</div>

---

## The Problem This Solves

E-commerce businesses generate enormous volumes of transactional data — but raw data alone drives no decisions. Executives need to know *where* revenue concentrates, *which* categories are eroding margin, and *when* demand spikes so capital can be deployed in advance.

This dashboard was built to answer exactly those questions: turning a multi-regional, multi-segment sales dataset into a single interactive command center that any stakeholder can navigate without SQL, Python, or a BI licence.

---

## Dashboard Preview

![Dashboard Overview](https://github.com/user-attachments/assets/be1731c0-c9b5-4456-a0aa-2f6fbaff267c)
![KPI Summary](https://github.com/user-attachments/assets/a16fb658-c98e-4ca3-a3ed-1c761623146c)

---

## Key Findings & Business Implications

| Finding | Strategic Implication |
|---|---|
| **North America & Europe** dominate revenue share | Defend core markets; optimize margin, not volume |
| **Electronics & Furniture** lead revenue *and* profitability | Double down on inventory depth and promotional investment |
| **Corporate customers** carry significantly higher AOV | Justify a dedicated account management and pricing tier |
| **Q4 drives disproportionate demand** | Front-load inventory procurement and campaign budgets by September |
| **Several high-volume regions operate at compressed margins** | Trigger immediate pricing review or supplier renegotiation |

These are not observations — they are **prioritized, actionable levers** mapped directly to revenue, margin, and operational efficiency.

---

## What the Dashboard Tracks

| KPI | Why It Matters |
|---|---|
| Total Revenue | Top-line health across all markets and segments |
| Units Sold | Volume trends by product, category, and period |
| Profit Margin % | Profitability signal — prevents revenue-without-returns growth |
| Regional Sales Distribution | Identifies concentration risk and expansion white space |
| Top Products & Categories | Powers SKU-level inventory prioritization |
| Customer Segment Contribution | Corporate vs. consumer revenue split for go-to-market strategy |
| Month-over-Month Growth | Momentum tracking and early seasonality detection |

---

## How It's Built

### Data Preparation
Raw transactional data cleaned and standardised using Excel filters, Text-to-Columns, `IF` logic, and date decomposition. All inconsistencies resolved upstream — before a single aggregation runs — so no error propagates into the analysis layer.

### Analysis Layer
Dynamic `PivotTables` aggregating across region, product category, customer segment, and time. Cross-sheet KPIs computed via `INDEX-MATCH`, `SUMIFS`, and `IFERROR` — resilient to data updates without formula rewrites.

### Dashboard Layer
Executive-facing interface with native **Slicers** for drill-down by region, segment, or time period. **Conditional formatting** for instant trend identification. Custom **combo, column, line, and donut charts** tuned for KPI storytelling rather than data decoration.

---

## Technical Architecture

```
Raw Data Sheet
      │
      ▼
Data Cleaning & Transformation (IF, Text-to-Columns, Date Logic)
      │
      ▼
PivotTable Analysis Layer (Region × Category × Segment × Time)
      │
      ▼
Formula Engine (INDEX-MATCH, SUMIFS, IFERROR — cross-sheet)
      │
      ▼
Interactive Dashboard (Slicers, Conditional Formatting, Custom Charts)
```

**Stack:** `Microsoft Excel` · `PivotTables` · `INDEX-MATCH` · `SUMIFS` · `Conditional Formatting` · `Slicers` · `Custom Charts`

---

## Business Impact

This dashboard directly enables three classes of decisions:

**1. Market Prioritisation**
Identify which regions to defend (high margin, high volume), grow (high volume, recoverable margin), or fix (high volume, structurally compressed margin) — based on data, not intuition.

**2. Inventory Optimisation**
Align procurement and stock planning with Q4 demand curves and top-category performance data, reducing both stockouts and overstock carrying costs.

**3. Margin Recovery**
Flag high-volume, low-margin geographies for targeted pricing review or supply chain renegotiation — turning operational data into a CFO-ready action list.

---

## Skills Demonstrated

This project was designed to reflect the analytical rigour expected in data-driven consulting and business intelligence roles:

- **Data thinking:** structured problem decomposition before touching a single cell
- **Technical execution:** advanced Excel — not just formulas, but an integrated analytical pipeline
- **Business translation:** every chart and KPI is framed around a decision, not just a metric
- **Executive communication:** the dashboard is built for a non-technical audience without dumbing down the analysis

---

## Roadmap

- [ ] **Power Query** — automated data refresh and transformation pipeline, eliminating manual cleaning steps
- [ ] **Power BI version** — DAX measures, row-level security, and scalable enterprise distribution
- [ ] **Forecasting layer** — trend extrapolation for Q-ahead demand planning

---

## About

Built as part of a structured analytics and consulting programme, applying real-world BI methodology to a global e-commerce dataset. Designed to reflect the standards expected in data analytics, management consulting, and corporate finance roles.

---

<div align="center">

*If you found this useful, a ⭐ on the repo goes a long way.*

</div>

