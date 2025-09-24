# 📊 Superstore Sales Analysis (Excel Project)

## 📌 Project Overview
This project analyzes the **Superstore dataset (9,994 records)** using **Excel** to explore sales, profit, and profitability trends.  
The goal is to practice **data cleaning, pivot table analysis, and visualization** as part of building a data analysis portfolio.

---

## 🔍 Dataset
- Source: Kaggle (Superstore Dataset by vivek468)  
- Rows: 9,994  
- Columns: 21 (including Order Date, Ship Mode, State, Category, Sales, Profit, etc.)

---

## ⚙️ Steps Performed

### 1. Data Cleaning
- Removed duplicates (based on Row ID + Order ID + Product ID).  
- Fixed inconsistent date formats for **Order Date** and **Ship Date**.  
- Checked for missing/blank values.  
- Added calculated fields:  
  - **Profit Margin** = Profit ÷ Sales  
  - **Year, Month, Quarter** (from Order Date)

### 2. Data Analysis with PivotTables
We explored the data with the following pivot tables:

#### 2.1 Analyze Total Sales by Region
- **Region → Rows**  
- **Sales → Values**  
- **Profit → Values** (optional)  
✅ Shows which region brings the most revenue and profit.

#### 2.2 Analyze Sales by Category and Sub-Category
- **Category → Rows**  
- **Sub-Category → Rows (nested under Category)**  
- **Sales → Values**  
- **Profit Margin → Values (Average)** (optional)  
✅ Highlights which sub-categories are most profitable (and which lose money).

#### 2.3 Analyze Sales Over Time
- **Order Date → Rows → Grouped by Year, Quarter, Month**  
- **Sales → Values**  
- **Profit → Values** (optional)  
✅ Displays sales and profit trends across years, quarters, and months.

#### 2.4 Analyze State-Level Performance
- **State → Rows**  
- **Sales → Values**  
- **Profit → Values**  
✅ Identifies which states perform best or worst in terms of profitability.

---

## 📊 Key Insights
- The **West region** generated the highest profit.  
- Certain sub-categories (e.g., Tables, Binders) had **negative profit margins**.  
- Sub-categories like **Envelopes, Labels, and Paper** achieved very high margins.  
- Sales steadily increased from **2014 to 2017**.  

---

## 📂 Files in this Repository
- `Superstore_Analysis.xlsx` → Excel workbook with PivotTables & Charts  
- `README.md` → Project documentation  

---

## 🚀 Tools Used
- Microsoft Excel (PivotTables, PivotCharts, Formulas)  

---

## 👤 Author
- Created by CraftedBySaqib
