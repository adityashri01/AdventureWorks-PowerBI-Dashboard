# AdventureWorks Power BI Dashboard

A multi-page Power BI dashboard built on the AdventureWorks dataset — covering sales performance, customer behavior, and product analysis.

---

## What This Project Is

I built this to practice end-to-end dashboard development in Power BI: connecting data, writing DAX measures, and designing something a business user could actually navigate. The AdventureWorks dataset is rich enough to simulate real reporting scenarios, so it made for good practice.

The result is a four-page dashboard — Executive, Customer, Product, and Continental views — each with its own focus and drill-through capability.

---

## What It Covers

- **KPI summary** — Revenue, Profit, Orders, and Return Rate at a glance
- **Revenue & profit trends** — time series from 2020 onwards, so you can see the trajectory
- **Customer segmentation** — breakdown by income level and occupation
- **Product performance** — which categories and SKUs are driving orders, and which have return rate issues
- **Drill-through navigation** — go from the executive summary into customer or product detail without losing context
- **Dynamic filters** — slice by year or product to focus on what matters

---

## Key Findings

- Revenue trended consistently upward after mid-2021
- Accessories had the highest order volume (~17K orders) across all categories
- Overall return rate is low at ~2.2%, but a handful of products sit above 3% — worth investigating
- Revenue per customer has been declining, suggesting lower average spend per visit over time
- Monthly order volume fluctuates noticeably — likely seasonal, worth modeling for inventory planning

---

## Dashboard Pages

### Executive View
![Executive Dashboard](Images/exec_dashboard.png)

### Customer View
![Customer Dashboard](Images/customer_dashboard.png)

### Product View
![Product Dashboard](Images/product_dashboard.png)

### Continental View
![Continental Dashboard](Images/continental_dashboard.png)

---

## Tools Used

- Power BI Desktop
- DAX (for calculated measures and KPIs)
- Excel / CSV (source data)

---

## Project Structure

```
AdventureWorks-PowerBI-Dashboard/
├── Data/          # Source dataset files
├── Dashboard/     # Power BI .pbix file
├── Images/        # Dashboard screenshots
└── README.md
```

---

## How to Use

1. Download the `.pbix` file from the `Dashboard/` folder
2. Open it in Power BI Desktop
3. Use the slicers, filters, and drill-throughs to explore the data

---

## What I'd Add Next

- Year-over-year growth and profit margin metrics
- Built-in forecasting using Power BI's analytics pane
- Customer Lifetime Value (CLV) calculation
- A cleaner, more consistent color theme across all pages

---

## About

Built by **Aditya Shrivastav** as part of an ongoing data analytics portfolio.  
Feedback and suggestions are welcome — open an issue or connect on LinkedIn.
