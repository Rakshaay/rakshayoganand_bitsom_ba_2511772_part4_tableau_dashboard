# Executive Sales Performance Dashboard

## Business Problem Summary

The objective of this project is to analyze sales, profitability, customer behavior, shipping performance, and return patterns using Tableau. The dashboard is designed to help business leaders identify key performance drivers, operational risks, and growth opportunities through interactive visualizations and KPI monitoring.

---

## Dataset Description

The dataset contains transactional sales data and includes information related to:

* Order details
* Sales revenue
* Profit
* Customer segments
* Product categories and sub-categories
* Geographic regions
* Shipping methods
* Discounts
* Returns
* Order and delivery dates

The dataset was used to evaluate overall business performance and support executive decision-making.

---

## Tableau Workbook Description

A Tableau workbook was created containing multiple worksheets and one executive dashboard.

The workbook includes:

1. Sales Trend View
2. Regional Performance View
3. Category Profitability View
4. Customer Segment Analysis View
5. Shipping Performance View
6. Discount vs Profit View
7. Return Analysis View
8. KPI Worksheets
9. Executive Dashboard

The dashboard combines key metrics and visualizations into a single interactive interface.

---

## Calculated Fields Created

### Profit Margin

Formula:

Profit / Sales

Purpose:
Measures the percentage of sales retained as profit.

### Cost

Formula:

Sales − Profit

Purpose:
Estimates business costs associated with sales.

### Average Order Value

Formula:

SUM(Sales) / COUNTD(Order Id)

Purpose:
Calculates average revenue generated per order.

### Return Rate

Formula:

SUM(Return Flag) / COUNT(Order Id)

Purpose:
Measures the percentage of orders that are returned.

### Shipping Delay Bucket

Logic:

* Fast (0–2 Days)
* Normal (3–5 Days)
* Delayed (6–8 Days)
* Highly Delayed (9+ Days)

Purpose:
Groups delivery performance into meaningful categories for analysis.

---

## Dashboard Components

The Executive Sales Performance Dashboard includes:

### KPI Cards

* Total Sales
* Total Profit
* Return Rate

### Visualizations

* Sales Trend
* Regional Performance
* Category Profitability
* Customer Segment Analysis
* Shipping Performance

Additional supporting views:

* Discount vs Profit
* Return Analysis

---

## Filters and Interactions Used

### Filters

The dashboard includes interactive filters for:

* Region
* Category
* Customer Segment
* Ship Mode
* Order Date

### Dashboard Interactions

Filter actions were implemented to allow users to click on a region and dynamically update all related charts throughout the dashboard.

This enables focused analysis of specific business segments and geographic areas.

---

## Key Business Insights

1. Sales performance varies throughout the year, indicating seasonal demand patterns.
2. The South region generates the highest sales revenue.
3. Technology products contribute the highest profitability.
4. Certain sub-categories outperform others within the same category.
5. Corporate customers generate the highest sales among customer segments.
6. Standard Class shipping experiences the highest delivery delays.
7. Returns represent a measurable cost to the business.
8. Higher discounts are associated with lower profit margins.
9. Technology products present significant growth opportunities.
10. Revenue concentration within a few regions and categories represents a business risk.

---

## Dashboard Story Summary

The dashboard reveals that business growth is primarily driven by strong regional performance, profitable product categories, and high-value customer segments.

While overall sales and profitability remain strong, operational challenges such as shipping delays, product returns, and aggressive discounting may impact long-term performance.

The dashboard highlights opportunities to expand profitable product lines, strengthen customer relationships, and improve logistics efficiency while mitigating business risks.

---

## Assumptions and Limitations

### Assumptions

* Sales and profit values are accurate and complete.
* Return Flag correctly identifies returned orders.
* Delivery days accurately represent shipping performance.
* Historical data is representative of business performance.

### Limitations

* Analysis is based only on historical transactional data.
* External market conditions are not included.
* Customer demographics are not available.
* Reasons for returns are not provided.
* Future demand forecasting is outside the scope of this dashboard.

---

## Screenshots Included

The following screenshots are included in the submission:

* screenshots/full_dashboard.png
* screenshots/sales_trend_view.png
* screenshots/regional_performance_view.png
* screenshots/category_profitability_view.png
* screenshots/filter_interaction_view.png

These screenshots demonstrate dashboard functionality, chart design, and interactive filtering features.


Full Dashboard
<img width="834" height="384" alt="full_dashboard" src="https://github.com/user-attachments/assets/878fad52-9357-48d3-bb95-fcccf94dbfff" />


Sales Trend view
<img width="683" height="409" alt="sales_trend_view" src="https://github.com/user-attachments/assets/a6567c33-37b7-4b36-aac6-9b9fd9902003" />


Regional Performance
<img width="586" height="268" alt="regional_performance_view" src="https://github.com/user-attachments/assets/e6e22ec9-bfc3-445f-8d8a-eaefd6dd3a63" />


Category profitiability
<img width="585" height="371" alt="category_profitability_view" src="https://github.com/user-attachments/assets/6d94a993-2574-421f-8c7e-90aa663882c6" />

Filter interaction
<img width="834" height="375" alt="filter_interaction_view" src="https://github.com/user-attachments/assets/c05574cd-9324-440d-a264-a7f329e39fbe" />
