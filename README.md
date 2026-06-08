# 📊 Regional Sales Performance Dashboard - Power BI

## 📘 Overview

The Regional Sales Performance Dashboard is a Power BI project designed to analyze sales performance, profit, orders, returns, delivery efficiency, and target achievement across different regions and product categories.

The dashboard provides interactive visualizations that help stakeholders monitor business performance, compare year-over-year growth, and make data-driven decisions.

---

## 🎯 Objectives

* Monitor overall sales and profitability across regions.
* Compare 2018 performance with 2017 results.
* Analyze category-wise sales against targets.
* Evaluate return rates and delivery delays.
* Identify top-performing regions and categories.
* Support business decision-making through interactive dashboards.

---

## 📊 Key Metrics

* 💰 Total Sales: 1.04M
* 📈 Total Profit: 128.9K
* 📦 Total Orders: 1.5K
* 🔄 Return Rate: 7%
* 🚚 Delivery Delay: 47.9%
* 🎯 Target Achievement: 36.06%

---

## 📈 Dashboard Pages

### 1️⃣ Overview Dashboard

* Total Sales KPI
* Total Profit KPI
* Total Orders KPI
* Return Rate KPI
* Delivery Delay KPI
* Target Achievement KPI
* Sales Trend (2018 vs 2017)
* Regional Performance Overview

### 2️⃣ Region Analysis

* Sales by Region
* Profit by Region
* Return Rate by Region
* Delivery Delay by Region
* Category Sales vs Target Analysis

### 3️⃣ Category Performance

* Sales vs Target by Category
* Profit by Category
* Category-wise Performance Analysis
* Target Achievement Comparison

### 4️⃣ Returns & Delivery

* Return Analysis
* Delivery Delay Analysis
* Region-wise Operational Performance

### 5️⃣ Key Insights

* Top Performing Categories
* Business Performance Trends
* Strategic Recommendations

---

## ⚙️ Tools and Technologies

* Microsoft Power BI
* Power Query
* DAX (Data Analysis Expressions)
* Data Modeling
* Interactive Visualizations
* Excel / CSV Dataset

---

## 🧠 Key DAX Measures

### Total Sales

```DAX
Total Sales =
SUM(Orders[Sales])
```

### Total Profit

```DAX
Total Profit =
SUM(Orders[Profit])
```

### Total Orders

```DAX
Total Orders =
DISTINCTCOUNT(Orders[Order ID])
```

### Sales Target

```DAX
Sales Target =
SUM(Target[Target Amount])
```

### Target Achievement %

```DAX
Target Achievement % =
DIVIDE([Total Sales],[Sales Target],0)*100
```

---

## 🌐 Interactive Report

Power BI Dashboard:

https://app.powerbi.com/links/-4EYx-sxMN?ctid=975c8213-07b6-4c7f-b850-f683a488501b&pbi_source=linkShare

---

## 👨‍💻 Author

**Myakala Abhivarma**

🎓 B.Tech – Data Science

📊 Power BI Developer | Data Analyst

📧 [myakalaabhivarma37@email.com](mailto:myakalaabhivarma37@email.com)

🔗 LinkedIn: https://www.linkedin.com/in/abhivarmamyakala

💻 GitHub: https://github.com/abhivarmamyakala

---

## ⭐ Project Outcome

This dashboard provides comprehensive business insights into sales, profitability, targets, returns, and delivery performance. It helps organizations identify growth opportunities, improve operational efficiency, and make informed business decisions through interactive analytics.

⭐ If you found this project useful, don't forget to star this repository!

