# Part 4: Tableau Executive Dashboard & Data Storytelling

## Student Details

**Name:** Divyansh Goel
**Student ID:** 25111001

---

# Business Problem Summary

The objective of this project is to develop an executive Tableau dashboard that enables retail leadership to monitor business performance across sales, profitability, customer segments, product categories, shipping performance, discounts, and return patterns. The dashboard supports data-driven decision-making by presenting key performance indicators and interactive visualizations in a single view.

---

# Dataset Description

The analysis uses the provided **dashboard_sales_data.xlsx** dataset containing retail transaction information.

The dataset includes fields such as:

* Order Date
* Sales
* Profit
* Category
* Sub Category
* Customer Segment
* Region
* Ship Mode
* Delivery Days
* Discount
* Return Flag

---

# Tableau Workbook

The dashboard was created using Tableau and saved as:

**tableau/executive_dashboard.twbx**

---

# Calculated Fields Created

The following calculated fields were created:

* Profit Margin
* Cost
* Average Order Value
* Return Rate
* Shipping Delay Bucket

These calculations help evaluate profitability, customer value, return behaviour, and delivery performance.

---

# Dashboard Components

The executive dashboard contains:

* Total Sales KPI
* Total Profit KPI
* Profit Margin KPI
* Sales Trend View
* Regional Performance View
* Category Profitability View
* Customer Segment View
* Shipping Performance View
* Discount vs Profit View
* Return Analysis View

---

# Filters and Dashboard Interactions

Interactive filters included:

* Region
* Category
* Customer Segment
* Ship Mode
* Order Date

Dashboard filter actions were applied so that selecting values updates all relevant charts.

---

# Key Business Insights

The dashboard highlights sales trends, regional performance differences, profitable product categories, customer segment performance, shipping efficiency, the relationship between discounts and profitability, and return behaviour to support business decisions.

---

# Dashboard Story Summary

The dashboard provides leadership with a consolidated view of retail performance. It identifies high-performing regions and categories, highlights operational risks related to shipping delays and returns, and supports decisions related to pricing, inventory, marketing, and customer management.

---

# Assumptions and Limitations

* Results are based on the provided dataset.
* The dashboard summarizes historical business performance.
* Business decisions should also consider external market conditions.
* Dashboard findings indicate trends and patterns but should be combined with business judgment.

---

# Tools Used

* Tableau
* Microsoft Excel
* GitHub
* Markdown

---

# Screenshots Included

* full_dashboard.png
* sales_trend_view.png
* regional_performance_view.png
* category_profitability_view.png
* filter_interaction_view.png

---

# Repository Structure

```text
part4_tableau_dashboard/
├── data/
├── tableau/
├── outputs/
├── screenshots/
└── README.md
```

---

# Conclusion

The Tableau Executive Dashboard provides an interactive and business-focused view of retail performance. It enables leadership to monitor key performance indicators, explore trends using filters, and identify opportunities for improving sales, profitability, customer experience, and operational efficiency.
