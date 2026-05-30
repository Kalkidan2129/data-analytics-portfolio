
# Walmart Store Sales

## Project Summary

Developed an interactive Power BI dashboard to analyze year‑over‑year sales trends across 45 Walmart stores in the United States from February 2010 to October 2012, a period following the 2008 recession. The solution integrates CSV data, custom calendar tables, conditional columns, and DAX measures to surface sales performance, holiday impacts, and unemployment influences.

---

## Business Problem

Walmart’s regional stores needed visibility into how post‑recession economic conditions affected weekly sales, especially during holiday periods and varying unemployment rates. Without a unified view, managers could not quickly identify underperforming locations or seasonal patterns.

---

## Objective

- Ingest and clean raw sales CSV data for 45 stores.
- Create time‑intelligence models (calendar table, date relationships) and derived metrics (YOY growth, CPI, unemployment impact).
- Deliver a polished, brand‑aligned Power BI dashboard for executive review.

---

## Tools & Technologies

- Power BI Desktop
- DAX
- Power Query (M)
- Excel (for data preparation)
- CSV data source
- Colaberry Power BI Cloud

---

## Project Workflow

- Import the Walmart sales CSV into Power BI Desktop.
- Build a Calendar table and refresh‑date table using DAX and Power Query.
- Establish relationships between the sales and calendar tables.
- Create conditional columns for holiday flags and unemployment groups, then apply custom sort orders.
- Develop DAX measures for total sales, average sales, sales YOY, and CPI, and embed logos and titles for branding.

---

## Key Insights

- Sales showed measurable YoY variation across the 2010‑2012 window, highlighting recovery patterns after the recession.
- Holiday weeks generated distinct spikes in weekly sales, confirmed by the Holiday Flag conditional column.
- Stores located in regions with higher unemployment rates exhibited lower average sales, as captured by the Unemployment Rate grouping.
- Custom month sorting enabled clear month‑over‑month visual comparisons, improving trend readability.

---

## Final Dashboard / Project Preview

![Final Dashboard](./screenshots/preview.png)

---

## Business Impact

- Enabled store managers to pinpoint periods of under‑performance and allocate resources proactively.
- Provided leadership with a single, branded dashboard to monitor recovery trends and seasonal effects.
- Facilitated data‑driven decision‑making for inventory and promotional planning across the 45‑store network.

---

## Files Included

- README.md
- project-data.json

---

## Generation Method

This project page was generated using: **AI-assisted project analysis**

---

## Portfolio Navigation

[← Back to Portfolio Home](../README.md)
