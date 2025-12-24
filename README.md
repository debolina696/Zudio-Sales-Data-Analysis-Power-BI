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

## ✅ Conclusion
This dashboard provides a **scalable and insight-driven sales analysis solution** for Zudio, combining robust data modeling, advanced DAX, and interactive visuals to support data-driven decision-making.
- Zudio Sales Dashboard link -  https://github.com/debolina696/Zudio-Sales-Data-Analysis-Power-BI/blob/main/Zudio%20Sales%20Dashboard.png
  # 📦 Zudio Inventory & Store Analysis Dashboard (Page 2)

## 🔍 Page Overview
This dashboard page focuses on **inventory, store operations, and workforce analysis** across Zudio outlets.  
It provides insights into **store distribution, staff strength, store ownership type**, and **manager-level performance**, supported by **detailed tooltip tables** for granular drill-through analysis.

---

## 🧱 Analytical Focus Areas
- Store-wise sales contribution
- City & State-wise store distribution
- Owned vs Rented store analysis
- Staff strength and store capacity
- Manager and customer-level sales breakdown

---

## 📌 Key KPIs
- **Total Staff Count**
- **Total Store Count**
- **Average Store Area Size**
- **Owned Store Count**
- **Rented Store Count**
- **Total Managers Count**

---

## 📊 Visuals & Insights
- **Total Sales by Store Address**
  - Identifies high and low performing store locations
- **City-wise Total Sales vs Store Count**
  - Compares sales contribution against store density
- **State-wise Store Count**
  - Distribution of stores across states
- **Customer ID-wise Details**
  - Total sales, units sold, and order count per customer
- **Manager ID-wise Details**
  - Sales performance mapped to store managers
- **Analytical Field (AI-assisted)**
  - Quick insight suggestions based on sales and cost trends

---

## 🧾 Tooltip Drill-Through Tables
Custom **tooltip pages** are added to enhance analysis, showing:
- State → City → Store-level staff count
- Store ownership type (Owned / Rented)
- Staff strength per store
- Aggregated totals for quick comparison

These tooltips enable **context-aware insights** without navigating away from the main dashboard.

---

## 🧠 Business Value Delivered
- Evaluate **store efficiency vs manpower**
- Identify **overstaffed or understaffed locations**
- Compare performance of **owned vs rented stores**
- Monitor **manager-wise accountability**
- Support expansion and optimization decisions

---

## 🛠️ Techniques Used
- Tooltip Pages with detailed tables
- Star Schema filtering
- DAX-based aggregations
- Cross-filtering across visuals
- Interactive slicers for State, City, Store, Security Type

--- Zudio Inventory Dashboard Link https://github.com/debolina696/Zudio-Sales-Data-Analysis-Power-BI/blob/main/Zudio%20Inventory%20Analysis.png

## ✅ Conclusion
Page 2 strengthens operational visibility by combining **inventory metrics, store analytics, and workforce insights** with **interactive tooltip-driven exploration**, enabling data-driven retail optimization.
# 🗺️ Zudio Sales Drill-Through & Tooltip Analysis (Pages 3 & 4)

## 🔍 Page Overview
These pages enhance the Zudio Sales dashboard with **geographical insights, category deep-dives, and store-level drill-through analysis**.  
They are designed to support **exploratory analysis** using **map visuals, detailed tables, drill-through actions, and tooltip pages**.

---

## 🌍 Page 3: Geo Sales & Category Analysis

### 📌 Visuals Included
- **Map Visual (City-Level)**
  - Displays Total Sales, Total Profit, Store Count, and Staff Count
  - Bubble size and color indicate sales contribution
- **State → City → Month Detailed Table**
  - Drill-enabled table showing:
    - Total Sales
    - Total Profit
    - Month-wise breakdown
- **Category-wise Sales Distribution**
  - Donut chart showing sales split across:
    - Men
    - Women
    - Kids
- **Clothing Type-wise Sales**
  - Bar chart comparing sales across product types

---

## 📊 Category Performance Analysis
- Month-wise sales and profit comparison by category
- Identifies **seasonal demand patterns**
- Supports category-level strategic planning

---

## 🔁 Drill-Through Functionality
Drill-through actions are enabled from:
- **Map (City level)** → Category Details
- **Category visuals** → Store Age & Store Address Analysis
- **Sales visuals** → Store-level performance

This allows users to navigate seamlessly from summary to granular insights.

---

## 🧾 Page 4: Store Age & Address Drill-Through

### 📌 Drill-Through Table
- **Store Address**
- **Store Age**
- **Store Category**

Used to analyze:
- Performance based on store maturity
- Comparison between new and older stores
- Store location effectiveness

---

## 🧠 Tooltip Pages (Key Highlight)
Custom tooltip pages are implemented across visuals to display:
- Store Address
- Store Age
- Store Category
- Staff Count
- Store Ownership Type (Owned / Rented)

Tooltips provide **context-rich insights** without leaving the current visual.

---

## 🛠️ Techniques Used
- Drill-Through Pages
- Tooltip Tables
- Map Visuals with multi-metric encoding
- Cross-filtering & highlight interactions
- Hierarchical navigation (State → City → Store)

---

## ✅ Conclusion
The drill-through and tooltip pages transform the dashboard into a **fully interactive analytical solution**, enabling users to move from **high-level KPIs to store-level details** while maintaining analytical context and usability.
-DrillThrough link - 
