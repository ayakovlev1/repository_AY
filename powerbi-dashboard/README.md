# 📊 Power BI Sales Dashboard – Superstore Dataset

This project presents an interactive Power BI report that analyzes sales performance, customer behavior, and product trends using the [Superstore](https://community.tableau.com/s/question/0D54T00000CWe9jSAD/sample-superstore) dataset.

The dashboard was designed as part of a data analytics portfolio and demonstrates the use of KPIs, DAX measures, slicers, and visual storytelling to support business decision-making.

---

## ✅ Key Features

- Dynamic filters by region, year, and customer type
- DAX-based customer segmentation (new vs returning)
- Clean and professional layout using KPI cards, bar charts, donut charts, and tables
- Documentation of all data transformations and metrics

---

## 📂 Views Included in the Report

###1️⃣ **Main Dashboard Overview**
- Total Sales, Orders, Clients, and Average Ticket
- Monthly sales trend by year (`Mes Pedido` & `Año Pedido`)
- Slicers: Region and Year
- Insight: Seasonal sales peaks in November and December

### 2️⃣ **Product Performance**
- Top 10 best-selling products by revenue
- Percentage contribution to total sales
- Region-wise breakdown of sales
- Insight: High concentration of revenue in a few key items

### 3️⃣ **Customer Segmentation**
- Donut chart: New vs Returning customers
- Sales distribution by customer type
- Slicers: Year & Region
- Insight: Majority of revenue comes from returning customers, but new acquisition is declining over time

### 4️⃣ **Data Preparation Summary**
- Description of all data cleaning steps:
  - Removed columns: `Country`, `Row ID`
  - Created fields: `Año Pedido`, `Mes Pedido`, `Trimestre Pedido`
  - Created `Tipo Cliente` using DAX
  - Measures: `Ticket Promedio`, `% Region`, `% Tipo Cliente`
- Includes DAX formulas and logic behind transformations

---

## 📷 Screenshots

---

## 🛠️ Tools Used

- **Power BI Desktop**
- **DAX** for calculated columns and measures
- **Excel / CSV** dataset input

---

## 📁 Files Included

- `Dashboard_Ventas.pbix`: Main Power BI report
- `README.md`: This documentation
- `img/`: Folder containing screenshots of the report

---

## 📌 Author

Alexander Yakovlev  
  
