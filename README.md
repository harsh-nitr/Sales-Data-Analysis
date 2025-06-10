# Sales-Data-Analysis 
# 📊 Power BI Sales Performance Dashboard

A fully interactive Power BI dashboard designed to deliver deep insights into product performance, sales trends, and customer behavior across various metrics like Net Sales, Profit, Discount, Quantity Sold, and more.

![Dashboard Screenshot](path-to-screenshot.png)

---

## 🚀 Project Overview

This project leverages Power BI's data modeling and visualization capabilities to help stakeholders:

- Monitor overall sales performance
- Identify top and bottom performing products
- Analyze trends over different time intervals
- Understand the impact of discounting
- Compare performance between any two user-selected periods

---

## 📌 Objectives Achieved

1. 📈 **Top/Bottom 5 Products**
   - Based on Sales, Profit, and Quantity Sold

2. 📊 **Sales Trends Over Time**
   - View sales by Day, Month, Quarter, and Year using a dynamic date hierarchy

3. 🔄 **Relationship Between Sales & Profit**
   - Scatter plot showing correlation and trendlines

4. 🆚 **Compare Two Time Periods**
   - Users can select any two date ranges to compare Sales, Profit, and Quantity Sold

5. 🧾 **Average Discount by Category**
   - Grouped by discount tiers to identify patterns

6. 🛒 **Total Number of Orders**
   - Card visual and supporting trend breakdown

7. 🎛️ **Detailed Order-Level Metrics**
   - Visual filters for:
     - Product
     - Date
     - Customer ID
     - Promotion Category

8. 🗺️ **Sales by City**
   - Map and bar charts representing regional sales distribution

---

## 🧱 Data Model

This report uses a **star schema**:

- **Fact Table**:
  - `Fact Table` (Net Sales, Profit, Quantity Sold, Discounts, etc.)

- **Dimension Tables**:
  - `Dim Product`
  - `Dim Customer`
  - `Dim Promotion`
  - `Dim Date`

All relationships are **one-to-many**, with appropriate keys defined between fact and dimension tables.

---

## 📂 Folder Structure

