# BlinkIT Grocery Sales Analysis - Power BI Project

## 📊 Project Overview
This Power BI project delivers an in-depth sales performance analysis for BlinkIT, a leading online grocery delivery platform in India. The dashboard visualizes key metrics such as product-level sales, outlet performance, and consumer purchasing trends across various outlet types and locations.

## 🎯 Objective
The primary objective is to derive actionable business insights by analyzing product visibility, outlet characteristics, and item attributes. The goal is to support business decisions like product placement, outlet expansion, and inventory optimization.

## 🧾 Data Source
- **File Name**: `BlinkIT Grocery Data.xlsx`
- **Sheet**: BlinkIT Grocery Data
- **Total Records**: ~8000 rows
- **Key Columns**:
  - `Item Type`, `Item Fat Content`, `Item Weight`, `Item Visibility`
  - `Outlet Size`, `Outlet Location Type`, `Outlet Type`, `Establishment Year`
  - `Sales`, `Rating`

## 🧹 Data Cleaning & Transformation
- Standardized categorical fields (e.g., Item Fat Content)
- Handled missing values in `Item Weight` using average imputation
- Created calculated columns in Power BI:
  - Total Sales per Outlet
  - Average Sales by Product Type
  - Visibility Index
- Used DAX measures for dynamic KPIs

## 📈 Dashboard Features
The Power BI dashboard includes the following components:
- **KPI Cards**: Total Sales, Average Rating, Total Items, Number of Outlets
- **Sales Breakdown**:
  - By `Item Type`
  - By `Outlet Type` & `Location`
- **Trend Charts**:
  - Yearly sales trends
  - Impact of item visibility on sales
- **Filters**:
  - By Year, Item Type, Outlet Type
  - Interactive slicers for custom analysis

## 🔍 Key Insights
- **Supermarket Type 1** outlets dominate in sales volume
- Higher sales observed for items with medium visibility
- `Fruits and Vegetables`, `Snack Foods` lead in revenue
- Tier 3 locations contribute significantly to total sales
- Outlets established post-2015 have relatively lower performance

## 🛠️ How to Use
1. Download the `.pbix` file from the repository
2. Open in [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
3. Refresh data if needed using the `BlinkIT Grocery Data.xlsx`
4. Interact with the dashboard using filters & slicers

## 🖼️ Dashboard Preview
_![image](https://github.com/user-attachments/assets/a55baec3-fb64-4e38-a47d-761f1497819a)_

## 📦 Files Included
- `blinkit project.pbix` – Power BI dashboard file
- `BlinkIT Grocery Data.xlsx` – Dataset used in the analysis
- `README.md` – Project documentation

## 👨‍💼 Author
**Pawan Bindha**  
Data Analyst  
[Linkedin](https://www.linkedin.com/in/pawanbindha/)

---

> This project serves as a portfolio piece and demonstrates proficiency in Power BI, data cleaning, DAX, and dashboard storytelling tailored for retail analytics.
