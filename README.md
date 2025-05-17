# 🛒 Retail Inventory Power BI Report

## 📊 Overview

This multi-page report provides a comprehensive analysis of retail performance between **January 2022 and January 2024**. It explores sales trends, inventory health, product category performance, and regional metrics to guide data-driven retail decisions.

Built using Power BI, the report enables stakeholders to identify sales patterns, optimize inventory, and understand revenue distribution at both macro and granular levels. This is a personal, original, and unguided project to reinforce a stimulation of a real world data analyst responsibility. The data used in this report is from a Kaggle dataset which contains daily records of retail inventory and sales across multiple stores and regions. Some of the columns included are: Date, Store ID, Category, Region, Inventory Level, Units Sold, and Demand Forecast. Many custom DAX measures were created to support various analyses and visuals. The original dataset can be found [here](https://www.kaggle.com/datasets/anirudhchauhan/retail-store-inventory-forecasting-dataset).

---

## 💼 Skills Demonstrated
- Interactive Report Design
- DAX for custom KPIs and time intelligence
- Time Series Analysis
- Inventory and Sales Metrics
- Stakeholder-Oriented Storytelling


## 🔍 Business Questions Answered

### 📅 **How do sales vary over time?**
- **Steady revenue** is consistently observed across the two-year period, with total revenue exceeding **$550M**.
- Sales do not particularly display periodic spikes.
- Revenue is **fairly stable month-to-month**, with no significant downturns, but February of 2022 and 2023 experienced a decline in revenue.

---

### 🗓️ **Are there noticeable patterns across months or dates?**
- Not in particularm, but Q4 months (October–December) seem to consistently peak without experiencing downturns unlike other quarters.
- A recurring **uptick in sales around March and July** may correlate with seasonal promotions or clearance events.

---

### 📦 **Which product categories are most popular?**
- **By revenue**: 
  - Top categories include **Furniture ($111.5M)**, **Groceries ($110.98M)**, and **Clothing ($109.65M)** — all performing almost equally.
- **By units sold**:
  - **Furniture** leads with over **2 million units** sold, suggesting strong volume and value.

---

### 💵 **What is the average spending per transaction?**
- The **Average Order Value (AOV)** across all categories is **$55.16**.
- **Furniture and Electronics** have the highest AOV, implying larger-ticket items per purchase.
- **Groceries and Toys** yield smaller transaction sizes, aligned with high-frequency, low-cost items.

---

### 📊 **What is the distribution of transaction sizes (quantity)?**
- Most purchases fall in the **low to medium quantity range**, indicating single or small-batch buying behavior.
- No dominant bulk purchasing patterns, even in high-volume categories like Groceries.

---

### 📈 **Are there seasonal trends in sales?**
- Yes. Sales peak in:
  - **November–December**: Likely due to holiday shopping.
  - **March–April**: Possibly aligned with spring campaigns or fiscal-year budgets.
- These insights support the timing of promotions and inventory adjustments.

---

### 📦 **How healthy is the inventory over time?**
- **Inventory levels align closely with forecasted demand**, showing a **96% forecast accuracy**.
- The **stock-to-sales ratio** remains around **2.01**, suggesting a safe inventory buffer without major overstocking.

---

### 🌍 **How do regions perform comparatively?**
- All four regions (East, North, South, West) contribute nearly **equally** (~25% each) to overall revenue.
- Suggests balanced market penetration and uniform performance across geographic areas.

---

### 🔗 **Are there correlations between inventory and sales metrics?**
- Positive correlation observed between **inventory value** and **monthly revenue**, confirming that **high stock availability** supports higher sales.
- No indication of overstocking affecting profitability due to well-managed forecast-to-sales alignment.

---
