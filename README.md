# 📊 Pilgrim – Business Intelligence Intern Assignment

## 📌 Project Overview
This project was completed as part of the Business Intelligence Intern assignment for Pilgrim.

The objective of this project is to analyze product-level data and build a meaningful dashboard to help the business team understand revenue performance, inventory status, brand contribution, and discount impact.

---

## 🛠 Tools & Technologies Used

- Python (Pandas, NumPy)
- Matplotlib & Seaborn
- Google Looker Studio
- Google Colab

---

## 📂 Dataset Description

The dataset contains the following fields:

- Product Name  
- Description  
- Brand  
- Category  
- MRP Price  
- Selling Price  
- Discount  
- Discount Percentage  
- Quantity  
- Revenue  
- Stock  
- Stock Value  
- Availability  

---

## 🧹 Data Cleaning & Feature Engineering

The following preprocessing steps were performed:

- Handled missing values using business logic
- Filled missing MRP values based on selling price validation
- Filled missing stock, quantity, and selling price using category median
- Standardized column names (lowercase with underscores)
- Converted appropriate data types
- Created new calculated columns:

  - **Discount = MRP – Selling Price**
  - **Discount % = (Discount / MRP) × 100**
  - **Revenue = Quantity × Selling Price**
  - **Stock Value = Stock × Selling Price**

- Rounded numerical columns for better readability

---

## 📊 Key KPIs

- **Total Revenue:** 1.9Bn  
- **Total Stock Value:** 1.8Bn  
- **Total Products:** 10K  
- **Average Discount %:** 27%  
- **Top Revenue Category:** Team Sports  
- **Highest Discount Brand:** Eaton, Espinoza and Casey  

---

## 📈 Dashboard Insights

### 🔹 Revenue Distribution
Revenue is well distributed across top categories and brands, reducing dependency on a single segment.

### 🔹 Discount vs Revenue
Moderate discounts (around 27–28%) generate strong revenue, while higher discounts do not necessarily increase performance.

### 🔹 Revenue vs Stock Value
A positive relationship exists between revenue and stock value, indicating that high-selling categories require greater inventory investment.

### 🔹 Top Performing Products
Fan, Dock, and Freezer generate the highest sales volume and revenue.

### 🔹 Risk Product Analysis
Products with:
- Revenue below average  
- Stock value above average  

These products may block working capital and require inventory optimization strategies.

---


## 📎 Project Links

- 🔗 Looker Studio Dashboard: https://lookerstudio.google.com/reporting/31813e0d-4c3b-4d33-920d-8516b1767f30  

