
# Walmart Store Sales

![Project Preview](./screenshots/preview.png)

## Project Summary

A comprehensive sales analysis dashboard evaluating year-over-year performance for 45 random Walmart stores across the US. The project analyzes sales trends between February 2010 and October 2012, focusing on the recovery period following the 2008 recession.

---

## Business Problem

Walmart stores faced significant sales impacts during the post-recession era, affecting discount and department store performance. There was a need to assess year-over-year sales trends to understand the recovery and impact of external factors on revenue.

---

## Objective

- Analyze year-over-year (YOY) sales performance across 45 US Walmart stores.
- Evaluate the impact of holiday weeks and unemployment rates on weekly sales.
- Develop a dynamic Power BI dashboard to visualize sales metrics and trends.

---

## Tools & Technologies

- Power BI
- Power BI Desktop
- DAX
- Excel
- Power Query
- CSV

---

## Project Workflow

- Imported Walmart sales data from CSV files into Power BI Desktop.
- Engineered a custom Calendar table using DAX for time-intelligence analysis.
- Established data relationships between the Walmart sales table and the Calendar table.
- Created conditional columns to categorize holiday flags and unemployment rates.
- Developed DAX measures for Total Sales, Sales Per Month, Average Sales, and Sales YOY.

---

## Key Insights

- Year-over-year sales growth can be tracked using DATEADD and DIVIDE functions in DAX.
- Holiday weeks serve as a critical variable in analyzing fluctuations in weekly sales.
- Unemployment rates provide a necessary context for understanding sales performance during the post-recession period.
- Custom sorting of month names and conditional categories is essential for accurate chronological and categorical reporting.

---

## Final Dashboard / Project Preview

![Final Dashboard](./screenshots/preview.png)

---

## Business Impact

- Enabled data-driven assessment of sales recovery trends following the 2008 recession.
- Provided visibility into the correlation between unemployment rates and store sales performance.
- Streamlined sales monitoring through the implementation of automated YOY growth metrics.

---

## Files Included

- README.md
- project-data.json

---

## Portfolio Navigation

[← Back to Portfolio Home](../README.md)
