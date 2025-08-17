# Power-Bi-Dashboard-blinkit-data
# BlinkIT Grocery Sales Analysis (Power BI)

## Project Overview
This project analyzes **BlinkIT grocery sales data** to generate business insights using **Power BI dashboards**.  
The goal is to help the business understand **sales performance, customer behavior, and product demand trends** in order to improve decision-making, optimize inventory, and drive revenue growth.  

The repository includes:  
- Raw dataset (`BlinkIT Grocery Data.xlsx`)  
- Power BI dashboard file (`Blinkit Sales Project.pbix`)  
- Documentation of insights and findings  

---

## Business Objectives
1. Analyze overall sales performance across categories and time.  
2. Identify top-performing and underperforming product categories.  
3. Understand customer purchasing patterns by demographics and region.  
4. Highlight demand trends to optimize **inventory management**.  
5. Provide actionable insights for **marketing campaigns** and **sales strategy**.  

---

## Project Structure
├── BlinkIT Grocery Data.xlsx # Source dataset
├── Blinkit Sales Project.pbix # Power BI dashboard
├── README.md # Documentation

---
## Data Description
The dataset contains grocery sales transactions, with the following key fields:
- **Item_Identifier** – Unique product code  
- **Item_Weight** – Weight of product  
- **Item_Fat_Content** – Low Fat / Regular  
- **Item_Visibility** – Percentage of display area allocated  
- **Item_Type** – Category of product (e.g., Dairy, Fruits, Beverages, Snacks, etc.)  
- **Item_MRP** – Maximum Retail Price  
- **Outlet_Identifier** – Store ID  
- **Outlet_Establishment_Year** – Store opening year  
- **Outlet_Size** – Small / Medium / High  
- **Outlet_Location_Type** – Tier 1 / Tier 2 / Tier 3 cities  
- **Outlet_Type** – Supermarket Type1, Type2, Grocery Store, etc.  
- **Item_Outlet_Sales** – Sales amount (target variable for analysis)  

---

##  Methodology
1. **Data Cleaning & Preparation**
   - Handled missing values in `Item_Weight` and `Outlet_Size`  
   - Standardized inconsistent values in `Item_Fat_Content`  
   - Derived additional features such as item age and store age  

2. **Exploratory Data Analysis**
   - Univariate and bivariate analysis of product sales  
   - Impact of item price (MRP) on sales  
   - Store-level sales performance  

3. **Power BI Dashboard Development**
   - Connected dataset to Power BI  
   - Built **interactive dashboards** with slicers (filters)  
   - Created DAX measures for KPIs (Total Sales, Avg. Sales, Growth %)  

---

## Dashboard Features
- **Sales Overview**
  - Total Sales, Average Sales per Outlet, Growth Rate  
  - Year-wise and Month-wise sales trends  

- **Product Analysis**
  - Top 10 selling products  
  - Sales by product type (Dairy, Beverages, Fruits, Snacks, etc.)  
  - Impact of 'Item_Fat_Content' and 'Item_Visibility'  

- **Customer & Store Insights**
  - Sales by location type (Tier 1, Tier 2, Tier 3)  
  - Sales by store size and outlet type  
  - Age of store vs performance  

- **Profitability & Pricing**
  - Relationship between MRP and sales volume  
  - Contribution of different MRP segments to revenue  

---

## Key Insights
1. **Top Categories** – Snacks and Dairy contribute the most to sales.  
2. **Customer Preference** – Regular fat content items have higher demand than low-fat ones.  
3. **Store Performance** – Tier 3 locations outperform Tier 1 in average sales.  
4. **MRP Impact** – Items with medium MRP ranges (100–200) have the highest sales.  
5. **Outlet Type** – Supermarket Type1 accounts for the majority of revenue.  
