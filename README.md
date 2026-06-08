# 🛍️ Orbital Retail Store — Sales Performance Tracker Dashboard

---

## 🧾 Overview

This project explores four years of retail sales data (2015–2018) from the Superstore dataset to uncover meaningful business trends and performance gaps across regions, categories, and customer segments.

The goal is simple: turn raw sales data into a clear, interactive Excel dashboard that helps retail managers quickly understand what’s working, what’s not, and where opportunities exist — without digging through thousands of rows of data.

---

## 🎯 Problem We’re Solving

Retail teams often struggle to get a quick, clear picture of overall performance. Important patterns like declining regions or underperforming categories can easily get lost in raw spreadsheets.

This project addresses this gap by answering:

- Where is the business performing well — and where is it struggling?
- Which products and regions are driving revenue?
- How is performance changing over time?

This dashboard is designed for retail managers, sales teams, and analysts who need fast insights without relying on complex BI tools.

---

## 📂 Dataset Snapshot

- **Source:** Kaggle — Superstore Sales Dataset  
- **Size:** ~9,800 rows and 21 columns  
- **Format:** CSV / Excel  

### Key Fields Used:

- **Order Date** → time-based trends and YoY analysis  
- **Region** → Central, East, South, West performance comparison  
- **Category & Sub-Category** → product-level insights  
- **Sales** → main performance metric  
- **Segment** → Consumer, Corporate, Home Office breakdown  
- **Customer Name** → identifying repeat and loyal customers  

---

## 🧰 Tools & Approach

Built entirely using **Microsoft Excel**.

### Key Tools:
- Pivot Tables  
- Slicers (Year & Month filtering)  
- Conditional Formatting
  
### Key Formulas:
- `SUMIFS` → category, region, segment-wise aggregation  
- `XLOOKUP / VLOOKUP` → data matching  
- YoY Growth → `(Current Year - Previous Year) / Previous Year`  

---

## 🧹 Data Preparation

- Missing values checked and handled  
- Order Date converted into proper date format  
- Duplicate records removed  
- Category names standardized  
- Created Year and Month columns for filtering  

---

## 📊 Exploratory Data Analysis (EDA)

### 📦 Category Performance
Technology is the top-performing category, followed by Furniture and Office Supplies.

### 👥 Customer Behavior
Consumer segment dominates order volume, contributing more than half of total transactions.

### 📈 Growth Trend
Strong and steady growth from 2015 to 2018, with YoY growth rising from ~20% to ~31%.

### 🌍 Regional Performance
- West and East outperform other regions  
- South region consistently underperforms  

### 🧠 Additional Insights
- Technology leads revenue every year  
- Home Office is the smallest segment  
- Phones and Chairs are top revenue drivers  

---

## 🔍 Key Insights

- **Technology** is the biggest revenue driver across all years  
- **South region** is the weakest performer and needs attention  
- Business shows strong and accelerating growth  
- **Consumer** segment drives most orders  
- A few products generate a large share of total revenue  

---

## 📌 Outcomes

### Key Metrics:
- **Total Revenue:** $2.26M  
- **Total Orders:** 9,800  
- **Average Order Value:** $231  
- **Peak YoY Growth:** ~31% (2018)  

### Business Impact:
- Identifies underperforming regions (South)  
- Highlights top categories and products  
- Shows clear growth trends  
- Supports fast, data-driven decisions  

---

## 📊 Dashboard Preview

Built in Microsoft Excel with interactive slicers for Year and Month filtering. All charts and KPIs update dynamically.
<img width="1217" height="434" alt="image" src="https://github.com/user-attachments/assets/682b9a65-4a8e-484a-88e1-3250fd433a11" />

---

## 📁 Project Structure

```bash
orbital-retail-dashboard/
│
├── data/
│   └── superstore_sales.csv
│
├── visuals/
│   └── Orbital_Retail_Store_Dashboard.PNG
│
├── dashboard/
│   └── Orbital_Retail_Store_Dashboard.xlsx
│
└── README.md
