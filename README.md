
# Adidas Sales Performance Dashboard – Power BI Case Study

This repository contains a complete Power BI dashboard built from an Adidas retail dataset.  
The goal of this case study is to analyze Adidas’ sales, profit, pricing, regional performance, and retailer contribution across the United States. The dashboard simplifies complex business data into clear and actionable insights.

---

## 📊 Project Overview

The Adidas dataset includes detailed transactional records such as:

- **Retailers:** Foot Locker, West Gear, Sports Direct, Amazon, Kohl’s, Walmart, etc.  
- **Sales Methods:** In-store, Outlet, Online  
- **Product Categories:** Men's Footwear, Women's Apparel, Athletic Footwear, Street Footwear, etc.  
- **Geography:** U.S. regions, states, and top cities  
- **KPIs:** Total Sales, Total Profit, Total Units Sold, Average Price  
- **Date Range:** 2020–2021  

This Power BI report highlights patterns, trends, and insights that help evaluate Adidas' overall business performance.

---

## 🚀 Key Features of the Dashboard

### ✔ **KPI Cards**
- **900M+ Total Sales**  
- **332M Total Profit**  
- **2M Units Sold**  
- **45 Average Selling Price**

### ✔ **Interactive Slicers**
- Date range  
- Retailer  
- Gender  
- Region  
- Top 5 Cities  
- Sales Method  

### ✔ **Visualizations Included**
- **Profit Analysis by Retailer**  
- **Total Sales by Product Category**  
- **Total Sales by Sales Method**  
- **Profit by Sales Method (Donut Chart)**  
- **Year & Quarter Sales Trend Line**  
- **Geographical Sales Map (State & Region)**  

### ✔ **Geospatial Insights**
- Visual map showing strongest and weakest performing states  
- Regional comparison (West, Northeast, South, Midwest, etc.)

---

## 🗂 Included Files

| File | Description |
|------|-------------|
| `POWERBI.pbix` | The complete Adidas Power BI dashboard |
| `dashboard_screenshot.png` | Preview of the report (optional) |
| `README.md` | Project documentation |

---

## 🧠 Data Cleaning & Modeling

Inside Power BI, the dataset was prepared using:

- Data type standardization  
- Handling null and inconsistent values  
- Date hierarchy creation (Year, Quarter, Month)  
- DAX measures for KPIs  
- Building relationships between fields  

---

## 🧮 Sample DAX Measures

**Total Sales**
```DAX
Total Sales = SUM('Adidas Data'[Total Sales])
