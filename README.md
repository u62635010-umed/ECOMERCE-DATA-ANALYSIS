# ECOMERCE-DATA-ANALYSIS
# E-Commerce Sales Dashboard (Power BI)

## 📌 Project Overview
This Power BI project is an **E-Commerce Sales Dashboard** built to analyze and visualize e-commerce business performance.  
It helps in tracking key metrics like **sales, profit, orders, customers, product performance**, and **regional trends** to support data-driven decision making.

---

## 🎯 Objectives
- Analyze overall **Sales & Profit performance**
- Identify **top selling products & categories**
- Track **customer behavior & purchase patterns**
- Compare **region/state-wise sales**
- Find **monthly/quarterly sales trends**
- Monitor **order quantity & shipping performance** (if available)

---

## 📊 Key KPIs
This dashboard includes:
- ✅ Total Sales
- ✅ Total Profit
- ✅ Total Orders
- ✅ Total Quantity Sold
- ✅ Average Order Value (AOV)
- ✅ Profit Margin %
- ✅ Top Customers
- ✅ Top Products / Categories
- ✅ Sales by Region / State / City
- ✅ Monthly Sales Trend

---

## 🧩 Dashboard Features
- Interactive **Slicers** (Date, Region, Category, Segment etc.)
- Trend analysis (Monthly / Quarterly Sales)
- **Top 10 Products & Customers** insights
- Category-wise and subcategory-wise analysis
- Regional sales heatmap / distribution
- Profit & sales comparison visuals

---

## 🛠 Tools & Technologies Used
- **Power BI Desktop**
- **Power Query** (ETL - Cleaning & Transformation)
- **DAX** (Measures & Calculations)
- Dataset: **CSV / Excel** (E-commerce transactions data)

---

## 📁 Dataset Information
The dataset includes fields like:
- Order ID
- Order Date
- Customer Name / ID
- Product Name
- Category / Sub-Category
- Sales
- Quantity
- Profit
- Region / State / City
- Segment (Consumer/Corporate/Home Office)

*(Mention dataset source here if it is from Kaggle or any public dataset.)*

---

## 🧹 Data Cleaning & Transformation (Power Query)
Main cleaning steps performed:
- Removed duplicates & null values
- Corrected data types (Date, Sales, Profit)
- Standardized region/category names
- Created new columns:
  - Month / Year
  - Profit Margin
  - Average Order Value (AOV)

---

## 📌 DAX Measures Used
Some key DAX measures:
- **Total Sales** = SUM(Sales)
- **Total Profit** = SUM(Profit)
- **Total Orders** = DISTINCTCOUNT(Order ID)
- **AOV (Average Order Value)** = [Total Sales] / [Total Orders]
- **Profit Margin %** = DIVIDE([Total Profit], [Total Sales])

---

## 📷 Dashboard Preview
(https://github.com/u62635010-umed/ECOMERCE-DATA-ANALYSIS/blob/main/Screenshot%202026-01-20%20174250.png)



---

## 🚀 How to Use
1. Download the `.pbix` file
2. Open it in **Power BI Desktop**
3. Use slicers to filter insights
4. Explore charts and KPIs for analysis

---

## 🔍 Insights From Dashboard
- Identifies which **product categories contribute most to revenue**
- Highlights **regions with highest sales and profit**
- Shows **seasonal trends in customer buying**
- Helps find **high-value customers**
- Detects low-profit products for improvement

---

## ✅ Conclusion
This Power BI dashboard provides a complete overview of an e-commerce business and helps stakeholders understand performance, customer trends, and product profitability for better business decisions.

---

## 👤 Author
**Umed**  
Data Analytics Student  
GitHub: *(add your link here)*  
LinkedIn: *(optional)*
