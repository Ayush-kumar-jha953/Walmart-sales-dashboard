# 🛒 Walmart Sales Dashboard — Power BI

> Power BI dashboard on Walmart Sales dataset (Kaggle) | Python · DAX · Power Query · Data Visualization

---

## 📌 Project Overview

This project is an end-to-end data analytics dashboard built on the **Walmart Sales dataset from Kaggle**. It explores weekly sales trends across 45 stores over multiple years, uncovering patterns in sales performance, fuel price impact, and store-level comparisons.

**Tools used:** Power BI Desktop · Python (Pandas) · Power Query · DAX · Matplotlib

---

## 📊 Dashboard Preview

> 📸 *Screenshot 1 — Full dashboard overview (all 4 visuals visible)*

![Dashboard Overview](screenshots/dashboard-overview.png)

---

## 🔍 Key Insights

### Graph 1 — Sales Trend by Year & Month *(Line Chart)*

> 📸 *Screenshot 2 — Line chart zoomed in*

![Sales Trend](screenshots/graph1-sales-trend.png)

- Sales peaked in **December** for both 2010 and 2011, indicating strong holiday season demand.
- In **2012**, the peak shifted to **June**, suggesting a change in consumer buying patterns.
- Overall sales show clear **seasonal fluctuations** across all years.

---

### Graph 2 — Avg Fuel Price vs Avg Weekly Sales *(Line/Area Chart)*

> 📸 *Screenshot 3 — Fuel price vs sales chart*

![Fuel vs Sales](screenshots/graph2-fuel-vs-sales.png)

- From **February onwards**, as average fuel prices rise, sales either **decrease or remain constant**.
- From **May onwards**, as fuel prices drop, average weekly sales show a **noticeable increase**.
- This suggests fuel price is a **key external factor** influencing consumer spending at Walmart.

---

### Graph 3 — Sales Distribution by Year *(Pie Chart)*

> 📸 *Screenshot 4 — Pie chart*

![Sales Distribution](screenshots/graph3-sales-distribution.png)

- **2011** recorded the **highest total sales** across all three years.
- **2012** recorded the **lowest total sales**, which aligns with the fuel price trends observed.
- The distribution highlights year-over-year decline in Walmart's weekly sales volume.

---

### Graph 4 — Avg Weekly Sales by Store & Year *(Clustered Column Chart)*

> 📸 *Screenshot 5 — Clustered column chart with slicer*
<img width="1147" height="255" alt="Screenshot 2026-05-29 180510" src="https://github.com/user-attachments/assets/9a776552-1353-48c0-a13e-0de5f2563a87" />

![Store Comparison](screenshots/graph4-store-comparison.png)

- Compares **average weekly sales across all 45 stores** for each year side by side.
- Helps identify which stores are **top performers** and which are underperforming.
- A **store slicer** is included to allow detailed filtering by individual store — since there are 45 stores, this makes it easy for stakeholders to focus on specific locations generating maximum sales.

---

## 📁 Repository Structure

```
walmart-sales-dashboard/
│
├── Walmart_Sales_Dashboard.pbix   # Power BI dashboard file
├── README.md                      # Project documentation
│
└── screenshots/
    ├── dashboard-overview.png     # Full dashboard view
    ├── graph1-sales-trend.png     # Line chart
    ├── graph2-fuel-vs-sales.png   # Fuel vs sales
    ├── graph3-sales-distribution.png  # Pie chart
    └── graph4-store-comparison.png    # Clustered column chart
```

---

## 📝 Summary

This dashboard provides a comprehensive view of Walmart's sales performance across **3 years (2010–2012)** and **45 stores**. The key takeaways are:

- Sales are heavily influenced by **seasonality** — December is the strongest month in most years.
- **Fuel prices have an inverse relationship** with consumer spending — higher fuel costs correlate with lower sales.
- **2011 was the strongest year** for Walmart sales, while 2012 saw a decline.
- Store-level analysis reveals significant **variation in performance** across the 45 stores, making the slicer a critical feature for business decision-making.

This project demonstrates skills in **data cleaning, transformation, DAX measure creation, and business-focused storytelling through visuals** — all core competencies for a data analyst role.

---

## 🗂️ Dataset

- **Source:** [Kaggle — Walmart Sales Forecasting](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting)
- **Records:** Weekly sales data across 45 stores
- **Features:** Store, Date, Weekly Sales, Holiday Flag, Temperature, Fuel Price, CPI, Unemployment

---

## 🙋 About Me

Aspiring Data Scientist | Open to internships worldwide
