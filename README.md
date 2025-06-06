# 🧩 Power BI DAX Practice: Sales Dataset Analysis

## 📌 Objective
This Power BI project demonstrates the practical use of **DAX functions** to build dynamic visualizations using a sales dataset containing clothing and accessory data.

Key focus:  
✅ Mastering `CALCULATE()`, `ALL()`, and `ALLEXCEPT()` functions  
✅ Creating DAX measures and calculated columns  
✅ Building insightful visualizations with proper filter context handling

---

## 📊 Tasks Completed

### 1. Matrix Visualization – **% Contribution to Total Sales**
- Created a DAX measure to calculate the **percentage contribution** of each product category to overall sales.
- Used `CALCULATE()` with `ALL()` to ensure **total sales remains constant** even when filters (like category or brand) are applied.


### 2. Card Visualization – **Category-wise Sales Only**
- Built a card visual that shows **sales by category**, responding **only to category filters**.
- Applied `CALCULATE()` with `ALLEXCEPT()` to **ignore other filters** (like brand or region) while preserving the category filter.
- Formula used:


## 🧠 Key Concepts Used
- `CALCULATE()` – Modify the filter context dynamically  
- `ALL()` – Remove all filters for a specified column  
- `ALLEXCEPT()` – Keep only the specified filters, ignore the rest  
- **Filter Context** – Understanding how filters affect DAX calculations  

---

## 🔍 Visuals Included
- Matrix: % contribution of each category to total sales  
- Card: Sales per category (isolated from non-category filters)  

---

## 🚀 Result
A clean, filter-aware report using DAX best practices — ideal for performance analysis and dashboard design!

---
