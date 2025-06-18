# Sales Performance Dashboard (Tableau Project)

## 📌 Project Overview

**Project Title:**  
Sales Performance Dashboard

**Objective:**  
To provide clear, interactive insights into regional and customer-segment-based profit performance, sales contribution, and order trends. This dashboard helps business teams make faster and more informed decisions.

**Problem Statement:**  
The sales team lacked a streamlined way to monitor real-time sales and profit performance across regions and customer segments. This made it difficult to identify high-performing areas or address issues in a timely manner.

---

## 🗂️ Data Description

**Data Source:**  
Sample Superstore dataset (available on platforms like Kaggle)

**Data Volume:**  
~10,000+ records

**Key Fields Used:**

- Sales
- Profit
- Region (Central, East, South, West)
- Customer Segment (Consumer, Corporate, Home Office, Small Business)
- Order Quantity
- Month

**Data Cleaning Steps:**

- Removed duplicates
- Handled missing values in profit and sales
- Standardized category names
- Ensured correct date formatting

---

## 🎯 Target Audience

- **Sales Managers:** To track performance across regions and customer segments
- **Business Analysts:** For deeper analysis into trends and profitability
- **Executives/Senior Management:** To make strategic decisions regarding resource allocation

---

## ⭐ Key Features

- **Profit by Region & Customer Segment (Stacked Bar):**  
  Highlights profit contribution by each segment and region.  
  *Insight:* Corporate segment dominates in Central and West; Consumer strong in South.

- **% Sales Contribution by Region (Pie Chart):**  
  - Central: 31.51% (₹4,699,167)  
  - West: 24.47% (₹3,649,748)  
  - East: 22.91% (₹3,416,466)  
  - South: 21.12% (₹3,150,219)

- **Profit vs Sales (Scatter Plot):**  
  Shows that higher sales don't always guarantee higher profit.  
  *Insight:* Some large orders gave minimal or negative profit.

- **Order Quantity by Month (Line Chart):**  
  - May: Highest order quantity (21,273 orders)  
  - February: Lowest (16,602 orders)  
  *Insight:* Seasonal spikes and consistent volume identified.

- **Interactive Filters:**  
  Based on User Grouping (A, B, C), allowing drill-down into custom segments.

---

## 🛠️ Tools and Techniques Used

- **Tool:** Tableau
- **Techniques:**  
  - Stacked bar charts  
  - Pie charts  
  - Scatter plots  
  - Line charts  
  - Interactive filters and parameters  

---

## 📋 Project Scope and Limitations

**Scope:**

- Regional and segment-based profit & sales analysis
- Monthly order quantity tracking
- Basic trends and relationships analysis

**Limitations:**

- Historical data only (no predictions)
- No consideration of external factors like discounts or inventory levels

---

## 📈 Outcome / Insights

- **Central Region:** Highest sales (31.51%) and strong profits in Corporate and Home Office segments.
- **South Region:** Strong profit in Corporate (₹168K) and Consumer (₹131K) segments despite lower sales.
- Some high-sales orders gave low or negative profit → Need cost control analysis.
- May: Peak order month → Useful for seasonal stock and promotion planning.
