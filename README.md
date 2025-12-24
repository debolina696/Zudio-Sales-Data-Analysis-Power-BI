# 📊 Zudio Sales Analytics Dashboard (Power BI)

## 🔍 Project Overview
This Power BI project analyzes **Zudio retail sales data** to deliver **actionable business insights** across time, geography, product categories, and management.  
The dashboard is built using a **star schema data model** with a dedicated **Date Table** to enable accurate **time intelligence calculations**.  
All visuals include **custom tooltip pages** for detailed drill-through analysis.

---

## 🧱 Data Model & Schema Design
- **Fact Table**: Sales transactions  
  - Sales Amount, Quantity, Cost, Profit, Profit Margin
- **Dimension Tables**:
  - DateTable (Date, Month, Month No, Year)
  - State, City, Store
  - Category, Clothing Type
  - Manager
- **Relationships**:
  - One-to-Many relationships from dimension tables to fact table
  - DateTable connected to Sales table for time intelligence
- **Measure Toggle Table**:
  - Enables dynamic switching between **Total Sales, Total Cost, Total Profit, Profit Margin**

---

## ⏱️ Time Intelligence
A custom **Date Table** is created and marked as a date table to support:
- **MTD (Month-to-Date)**
- **MoM % Change**
- **Last Month Sales**
- **3-Month Rolling Average**

Ensures consistent and accurate trend analysis across all visuals.

---

## 📌 KPIs Covered
- Total Sales (Dynamic Measure)
- MTD Sales
- MoM % Growth
- 3-Month Rolling Average
- Total Profit
- Profit Margin
- Total Cost

---

## 📈 Dashboard – Page 1 (Sales Overview)
- KPI Cards with dynamic measure toggle
- MTD Sales trend by Month
- 3-Month Rolling Average Sales trend
- Top 5 Cities by Total Sales
- Top 5 Managers by Total Sales
- Top 3 Clothing Types by Sales
- Category-wise Profit Contribution (Donut Chart)
- State-wise Sales Distribution (Pie Chart)
- Monthly Cost vs Profit comparison

All visuals include **interactive tooltips** for deeper insights.

---

## 🧠 Business Insights Enabled
- Identify top-performing **states, cities, and managers**
- Track **monthly growth and seasonality**
- Compare short-term vs long-term sales performance
- Analyze **profitability by category**
- Monitor cost and profit trends effectively

---

## 🛠️ Tools & Techniques Used
- Power BI Desktop
- DAX (CALCULATE, TOTALMTD, DATEADD, DIVIDE, AVERAGEX)
- Star Schema Modeling
- Calculation Group / Measure Toggle
- Tooltip Pages
- Time Intelligence Best Practices
- Zudio Sales Dashboard link - 

## ✅ Conclusion
This dashboard provides a **scalable and insight-driven sales analysis solution** for Zudio, combining robust data modeling, advanced DAX, and interactive visuals to support data-driven decision-making.
