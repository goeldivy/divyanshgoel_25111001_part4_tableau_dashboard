# Chart Selection Justification

## 1. Sales Trend View

**Business Question:** How are sales changing over time?

**Chart Used:** Line Chart

**Reason for Selection:** A line chart is the most appropriate visualization for showing trends and changes in sales over time.

**Fields Used:**

* X-Axis: Order Date (Month)
* Y-Axis: Sales

**Design Principle Applied:** Simple layout with a clear time sequence for easy trend identification.

**Mistake Avoided:** Avoided using pie charts or unordered charts, which are not suitable for time-series data.

---

## 2. Regional Performance View

**Business Question:** Which region performs best?

**Chart Used:** Horizontal Bar Chart

**Reason for Selection:** Bar charts make it easy to compare sales across regions.

**Fields Used:**

* Rows: Region
* Columns: Sales
* Color: Profit

**Design Principle Applied:** Descending order helps users quickly identify the highest-performing region.

**Mistake Avoided:** Avoided unnecessary 3D charts that can distort comparisons.

---

## 3. Category Profitability View

**Business Question:** Which product categories generate the highest profit?

**Chart Used:** Horizontal Bar Chart

**Reason for Selection:** Horizontal bars provide clear comparison of profit across categories and sub-categories.

**Fields Used:**

* Rows: Sub Category
* Columns: Profit
* Color: Profit

**Design Principle Applied:** Sorted bars improve readability and highlight the most profitable categories.

**Mistake Avoided:** Avoided clutter by keeping only relevant labels.

---

## 4. Customer Segment View

**Business Question:** Which customer segment contributes the most to sales?

**Chart Used:** Horizontal Bar Chart

**Reason for Selection:** The chart clearly compares sales among customer segments.

**Fields Used:**

* Rows: Customer Segment
* Columns: Sales
* Color: Profit

**Design Principle Applied:** Clear labels and simple comparison.

**Mistake Avoided:** Avoided excessive colors that distract from interpretation.

---

## 5. Shipping Performance View

**Business Question:** Which shipping mode has the longest delivery time?

**Chart Used:** Horizontal Bar Chart

**Reason for Selection:** It provides an easy comparison of average delivery days across shipping modes.

**Fields Used:**

* Rows: Ship Mode
* Columns: Average Delivery Days

**Design Principle Applied:** Easy-to-read comparison with consistent formatting.

**Mistake Avoided:** Avoided complex charts that reduce readability.

---

## 6. Discount vs Profit View

**Business Question:** How does discount relate to profit?

**Chart Used:** Scatter Plot

**Reason for Selection:** Scatter plots are ideal for showing relationships between two numerical variables.

**Fields Used:**

* X-Axis: Discount
* Y-Axis: Profit
* Color: Category

**Design Principle Applied:** Each point represents an observation, making patterns easier to identify.

**Mistake Avoided:** Avoided line charts because the data does not represent a time trend.

---

## 7. Return Analysis View

**Business Question:** Which categories have higher product returns?

**Chart Used:** Bar Chart

**Reason for Selection:** Bar charts clearly compare return rates across categories.

**Fields Used:**

* Rows: Category
* Columns: Return Flag / Return Rate

**Design Principle Applied:** Simple comparison with clear labels.

**Mistake Avoided:** Avoided pie charts because comparing return values is easier with bars.

---

# Dashboard Design Principles

The dashboard follows key visualization best practices:

* Consistent layout and formatting.
* Clear chart titles and labels.
* Interactive filters for deeper analysis.
* KPI cards displayed at the top for quick decision-making.
* Minimal clutter with a focus on business insights.
* Appropriate chart selection for each business question.
* Consistent color usage to improve readability.
* Dashboard actions and filters enable interactive exploration.
