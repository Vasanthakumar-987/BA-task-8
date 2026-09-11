# BA-T8 — Business Sales Performance Dashboard

[📊 View Dashboard on Tableau Public](https://public.tableau.com/shared/4NCDT9WX6?:display_count=n&:origin=viz_share_link)

## 📊 Project Overview

This project uses **Tableau Public** to analyze business sales across product lines, deal sizes, years, and countries.

The dashboard combines a **Treemap**, **Horizontal Bar Chart**, **Line Chart**, and **Filled Map** to identify major sales contributors, compare product performance, and explore yearly and geographic sales patterns.

---

## 🎯 Objective

To analyze sales contribution using a **Treemap in Tableau**, supported by three additional visualizations, and identify the product lines and deal-size segments that contribute most to overall sales.

---

## ❓ Problem Statement

Create a business sales dashboard to:

- Compare sales contribution by product line and deal size.
- Identify the highest- and lowest-selling product lines.
- Analyze recorded sales trends over time.
- Explore sales performance across countries.
- Generate insights that support further business analysis.

---

## 📁 Dataset Overview

The dashboard displays sales data across **2003–2005**, covering seven product lines and three deal-size categories: **Small, Medium, and Large**.

### Main Fields Used

| Purpose | Field | Usage |
|---|---|---|
| Sales Analysis | `Sales` | Calculate total sales using `SUM(Sales)` |
| Product Comparison | `Productline` | Compare sales across product lines |
| Deal-Size Analysis | `Dealsize` | Analyze Small, Medium, and Large deals |
| Yearly Trend | `Orderdate` | Group sales by year |
| Geographic Analysis | `Country` | Compare sales across countries |

### Product Lines

- Classic Cars
- Vintage Cars
- Motorcycles
- Trucks and Buses
- Planes
- Ships
- Trains

---

## 📈 Tableau Visualizations

### 1. Treemap — Sales Contribution by Product Line & Deal Size

The treemap compares sales contribution across combinations of product line and deal size.

- **Size:** `SUM(Sales)`
- **Colour:** `SUM(Sales)`
- **Labels:** Deal size and product line

Larger blocks represent greater sales contributions, while darker colours indicate higher sales values.

### 2. Horizontal Bar Chart — Sales by Product Line

The horizontal bar chart ranks product lines by total sales.

- **Rows:** Product line
- **Columns:** `SUM(Sales)`
- **Labels:** Total sales
- **Sorting:** Highest to lowest sales

This visualization makes it easy to identify leading and lower-selling product categories.

### 3. Line Chart — Yearly Sales Trend

The line chart displays recorded sales across 2003, 2004, and 2005.

- **X-Axis:** Year of order date
- **Y-Axis:** `SUM(Sales)`

This chart highlights changes in annual sales totals and identifies the year with the highest recorded sales.

### 4. Filled Map — Sales Performance by Country

The filled map shows the geographic distribution of sales.

- **Location:** Country
- **Colour:** `SUM(Sales)`

Darker shading represents higher sales, helping users compare contributions across markets.

---

## 🧩 Dashboard Features

- Four complementary visualizations in a single dashboard.
- Product-line rankings with visible sales values.
- Contribution analysis by product line and deal size.
- Yearly sales trend analysis.
- Country-level sales comparison.
- Consistent blue and teal colours.
- Online access through Tableau Public.

---

## 🔎 Key Insights

### Sales by Product Line

| Rank | Product Line | Total Sales |
|---|---|---:|
| 1 | Classic Cars | 3,919,616 |
| 2 | Vintage Cars | 1,903,151 |
| 3 | Motorcycles | 1,166,388 |
| 4 | Trucks and Buses | 1,127,790 |
| 5 | Planes | 975,004 |
| 6 | Ships | 714,437 |
| 7 | Trains | 226,243 |

*Sales figures follow the rounded labels shown in the dashboard. Currency is not specified in the displayed view.*

1. **Classic Cars generate the highest sales**, contributing approximately **3.92 million**, followed by **Vintage Cars** at approximately **1.90 million**.

2. **Trains record the lowest sales**, contributing approximately **0.23 million**.

3. **Medium-sized Classic Cars deals** form the largest individual segment in the treemap.

4. **Sales increase from 2003 to 2004**, with **2004** recording the highest annual sales among the displayed years.

5. **The recorded sales total for 2005 is lower.** The dataset’s date coverage must be checked before interpreting this as a full-year business decline.

6. **The United States stands out with darker shading on the map**, indicating a high sales contribution in the displayed view.

---

## 💡 Recommendations

### 1. Analyze Leading Product Lines

Prioritize further demand and inventory analysis for **Classic Cars** and **Vintage Cars**, as they contribute the most sales. Consider profit margins alongside sales when making business decisions.

### 2. Explore Deal-Size Contribution

Investigate medium-sized deals, particularly within Classic Cars, to understand which customer segments and purchasing patterns drive their contribution.

### 3. Review Lower-Selling Categories

Examine demand, pricing, and product availability for lower-selling categories such as **Trains** before deciding on promotional or inventory changes.

### 4. Compare Equivalent Time Periods

Verify whether 2005 contains a complete year of records. If it covers only part of the year, compare the same months across years to assess performance fairly.

### 5. Investigate Geographic Opportunities

Use country-level sales to identify markets for further analysis, considering customer demand, market size, and operating costs.

---

## 📝 Analysis Notes

- Sales contribution does not directly indicate profitability.
- Annual comparisons require complete and comparable reporting periods.
- Findings are based on the values and patterns displayed in the dashboard.

---

## 🛠️ Tools Used

- **Tableau Public** — Data visualization, dashboard development, and publishing
- **GitHub** — Project documentation and sharing

---

## 🌐 Live Tableau Dashboard

👉 [View the Business Sales Performance Dashboard on Tableau Public](https://public.tableau.com/shared/4NCDT9WX6?:display_count=n&:origin=viz_share_link)

---

## 📌 Project Summary

This project demonstrates how Tableau can present business sales data through contribution analysis, product rankings, yearly trends, and geographic comparisons.

The treemap highlights major product and deal-size contributors, while the supporting charts provide a broader view of sales performance. Together, these visualizations create a clear foundation for further business analysis.

---

## 👤 Author

**Vasanthakumar R**
**AADS25031**
