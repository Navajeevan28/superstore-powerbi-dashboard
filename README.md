# Superstore Sales & Profitability Dashboard

An end-to-end Power BI project analyzing sales, profit, and shipping performance for a retail superstore dataset, built to answer 12 real business questions across two dashboard pages.

# Overview
This project explores sales and profitability trends across regions, categories, customer segments, and time, using Power BI Desktop. It includes data cleaning in Power Query, a custom date table with time-intelligence DAX, and interactive visuals with slicers synced across pages.

# Dashboard Pages
- **Overview** — Total Sales, Profit, Orders, Profit Margin %, sales by region/category, top 10 customers, YoY growth trend
- **Profitability** — Profit by segment, discount vs. profit analysis, shipping time by ship mode, and a what-if discount cap simulator

# Business Questions Answered
1. What are total sales, profit, and order volume?
2. Which regions and categories drive the most sales?
3. How does profit margin vary by category?
4. Which state/region combination is most profitable? *(table with conditional formatting)*
5. At what discount level does profit turn negative?
6. Who are the top 10 customers by sales share?
7. Which customer segment is most profitable?
8. How long does an order take to ship, and does it vary by ship mode?
9. What is year-over-year growth in sales and profit?
10. Are best-sellers by quantity the same as best-sellers by revenue?
11–12. What-if analysis: simulated profit under different discount caps

# Tools & Techniques
- Power BI Desktop (Power Query, DAX, Data Modeling)
- Custom Date table + time-intelligence (SAMEPERIODLASTYEAR, DATEDIFF)
- Calculated measures: RANKX, DIVIDE, SWITCH, SUMX, CALCULATE
- What-if parameter for discount cap simulation
- Conditional formatting, synced slicers, custom theme

# Files
- `Superstore-Sales-Dashboard.docx` — full dashboard export
- Screenshots (if included)

# About
Built as a portfolio project while learning Power BI. Dataset: Sample Superstore dataset (Sales, Orders, Returns).
