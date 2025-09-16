# Superstore Sales Dashboard (Excel)

## Project Overview
This project involved analyzing and visualizing sales data from the US Superstore dataset using **Microsoft Excel**.  
The goal was to uncover key business insights through **data cleaning, transformation, and dashboard creation**.

---

## Tools & Skills Used
- Microsoft Excel
- Power Query (data cleaning & transformation)
- Pivot Tables & Charts
- Data Visualization Techniques

---

## Process

### 1. Data Cleaning (Power Query)
- Removed unnecessary columns (e.g., Row ID).
- Removed duplicates, reducing rows from ~9,000 to **5,009 unique records**.
- Converted *Sales* and *Profit* columns to currency format.
- Added a new calculated column for **Shipping Duration** (Ship Date – Order Date).

### 2. Data Analysis (Pivot Tables & Charts)
- **Top Performing Products**: Identified top 10 products by sales.
- **Sales by Category/Sub-Category**: Compared sales across categories and sub-categories.
- **Profitability Analysis**: Classified orders as profitable or unprofitable using profit values.
- **Monthly Sales Trends**: Created a line chart to track sales over time.
- **Sales by Region**: Categorized sales per US region.
- **Top 10 Customers**: Identified the top performing customers.

### 3. Dashboard Features
- Interactive slicers for filtering by *Region, Category, Segment, and Ship Mode*.
- Clean visual layout with summary metrics and charts.
- KPIs visualized using bar charts, line charts, and pivot tables.

---

## Dataset
- **data/sample-superstore.xlsx** → Raw dataset before cleaning (publicly available sample dataset).
- **dashboard/Superstore.xlsx** → Cleaned and transformed version with dashboard and pivot tables.
  
---

## How to Use
1. Download the raw Excel file from the data folder.
2. Download the Cleaned and Visualized Excel file from the dashboard folder.    
3. Open in Excel to interact with slicers, charts, and KPIs.

---

## Key Insights
- Top 10 products account for a significant share of total sales.
- Office Supplies dominates in sales volume, while Furniture yields higher profit margins.
- Year-end months show clear seasonal spikes in sales.
- Customer concentration: top 10 customers contribute heavily to revenue.
