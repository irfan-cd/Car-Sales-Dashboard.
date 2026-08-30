

# 🚗 Car Sales Analysis Dashboard | Power BI

## 📌 Project Overview
Developed an interactive Car Sales Dashboard in Power BI to analyze dealership sales performance, track key KPIs, compare year-over-year performance, and identify sales trends across vehicles, companies, colors, and dealer regions.

## 🎯 Business Problem
The dealership's sales data contained detailed transaction information, but it was difficult to quickly monitor overall performance and identify sales trends, high-performing vehicle categories, companies, and regions from the raw data.

## 🎯 Project Objective
Built a dynamic Power BI dashboard that transforms raw car sales data into interactive KPIs, visual analysis, and actionable business insights for monitoring sales performance and supporting data-driven decisions.

## 🛠️ Tools & Technologies
- **Power BI**
- **Power Query** – Data cleaning & transformation 
- **DAX** – KPI & time-intelligence calculations 
- **Data Modeling** – Relationships & Calendar Table 
- **Kaggle** – Dataset Source 

## 📊 Key KPIs
- **YTD Total Sales** 
- **MTD Total Sales** 
- **YoY Sales Growth** 
- **YTD Average Price** 
- **YoY Average Price Growth** 
- **YTD Cars Sold** 
- **YoY Cars Sold Growth** 
- **PYTD Comparison** 

## 📈 Dashboard Analysis
The dashboard includes:
- **Weekly Sales Trend** – Track sales performance over time 
- **Sales by Body Style** – Identify high-performing vehicle types 
- **Sales by Color** – Analyze vehicle color contribution 
- **Dealer Region Map** – Analyze geographical sales distribution 
- **Company-wise Sales** – Compare manufacturers by sales, cars sold, and average price 
- **Sales Details Table** – Drill down to individual transactions 
- **Interactive Filters** – Body Style, Dealer Region, Transmission, and Engine 

## 🔧 Key Technical Implementation
- Cleaned and validated the dataset using **Power Query**. 
- Created a dedicated **Calendar Table** for time-intelligence analysis. 
- Established a **one-to-many relationship** between the Calendar Table and sales data. 
- Developed **DAX measures** using `TOTALYTD()`, `TOTALMTD()`, `CALCULATE()`, `SAMEPERIODLASTYEAR()`, `DIVIDE()`, and `MAXX()`. 
- Implemented dynamic **conditional formatting** for KPI performance. 
- Highlighted the **maximum weekly sales** point dynamically. 

## 🔍 Key Insights
- **YTD Total Sales**: Reached $371.2M, with 23.6% YoY growth, indicating strong overall sales performance compared with the previous year. 
- **Sales Volume**: 13K cars were sold YTD, with volume increasing by approximately 2.62K cars compared with the previous-year period. 
- **Average Price**: YTD average selling price was approximately $28K, showing a 0.79% YoY decline, suggesting that sales growth was driven more by higher vehicle volume than by higher average prices. 
- **Weekly Trends**: Sales showed significant fluctuations, with the highest visible weekly sales reaching approximately $14.9M, indicating varying sales activity throughout the year. 
- **Body Style Demand**: SUVs were among the major contributors to total sales, highlighting strong demand for this vehicle body style. 
- **Color Choice**: Pale White accounted for the largest share of sales among the displayed colors, followed by Black and Red. 
- **Manufacturer Impact**: Sales contribution varied considerably across car manufacturers. Chevrolet, Ford, and Dodge were among the stronger contributors in the visible company analysis. 
- **Regional Performance**: Performance varied geographically, helping identify locations with stronger sales activity and opportunities for improvement. 

## 💡 Business Takeaway
Overall, the dealership is experiencing strong sales growth primarily through increased vehicle sales volume, while average selling price has slightly declined. This indicates an opportunity to maintain sales momentum while focusing on pricing strategy, high-demand vehicle types, and stronger-performing manufacturers and regions.

# 📸 Dashboard Preview

![Car Sales Analytics Dashboard]((https://github.com/irfan-cd/Car-Sales-Dashboard./blob/main/dashboard%20images/car%20sales%20overview%20preview.png))

---
![Car Sales Analytics Dashboard](https://github.com/irfan-cd/Car-Sales-Dashboard./blob/main/dashboard%20images/car%20sales%20details%20preview.png)

---





