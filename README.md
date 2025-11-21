# 🍦 Ice Cream Sales Analysis – Power BI Dashboard

A comprehensive Power BI dashboard built to analyze Ice Cream sales trends, revenue patterns, seasonal effects, and product performance.  
The project provides clear insights into how temperature, flavors, locations, and customer behavior influence total sales.

---

## 🎯 Project Objective
The goal of this project is to understand the major factors influencing ice cream sales and provide data-driven insights that help businesses:

- Identify high-performing flavors  
- Understand seasonal demand patterns  
- Analyze sales trends based on temperature  
- Identify top revenue-generating regions  
- Improve forecasting and supply planning  

This dashboard serves as a complete analytical tool for ice cream shop owners, distributors, and decision-makers.

---

## 📊 Key Insights
Some important findings from the analysis include:

- **Sales increase significantly as temperature rises**, showing a strong positive correlation.  
- **Certain flavors (like Vanilla & Chocolate)** contribute the highest portion of sales.  
- **Weekends show higher sales**, indicating customer buying behavior.  
- **Summer months outperform winter months** in both volume and revenue.  
- Specific regions or stores consistently achieve higher performance due to footfall or climate advantages.  
- Discounts and promotional offers increase sales but may reduce profit margin.

---

## 📁 Dataset Overview
The dataset contains typical Ice Cream sales attributes:

### **Sales Table**
- Date  
- Temperature (°C)  
- Flavors  
- Quantity Sold  
- Revenue  
- City / Region  
- Day of Week  
- Promotion Applied (Yes/No)  

### **Additional Dimensions**
(If included in your PBIX)
- Calendar Table  
- Weather Table  
- Store Details  

---

## 🧠 Data Model (Star Schema)
A clean and efficient star schema is used for this project:

**Fact Table:**
- Sales

**Dimension Tables:**
- Calendar (Date Dimension)
- Flavors
- Region / City
- Promotion
- Weather / Temperature Data

This structure supports better filtering, drilling down, and time-based analysis.

---

## 🧮 Key Measures (DAX)
Some of the essential DAX measures used:

- **Total Sales**  
- **Total Revenue**  
- **Average Temperature**  
- **Total Quantity Sold**  
- **Revenue by Flavor**  
- **Sales by Temperature Bucket**  
- **Daily/Monthly/Seasonal Sales Trends**  
- **Top Flavor / Bottom Flavor Analysis**  
- **Promotion Efficiency Metrics**  

---

## 📊 Dashboard Features

### 🟦 **Overview Page**
- Total Revenue  
- Total Quantity Sold  
- Avg. Temperature  
- Sales Correlation with Temperature  
- Yearly / Monthly Sales Trends  

### 🟩 **Flavor Performance**
- Best-selling flavors  
- Revenue contribution by flavor  
- Profitability comparison  
- Flavor ranking visual  

### 🟧 **Seasonal & Monthly Trends**
- Summer vs Winter performance  
- Peak sales months  
- Weekend vs Weekday patterns  

### 🟪 **Geographical Insights**
- City / Region-wise sales  
- Top-performing store locations  
- Temperature vs Sales by region  

### 🟫 **Promotion Impact Analysis**
- Effect of discounts on sales  
- Promo vs Non-promo revenue  
- Lost margin due to discounts  

---

## 🛠️ Tools Used
- **Power BI Desktop**  
- **Excel / CSV** (sales + weather data)  
- **Power Query** (data cleaning & transformation)  
- **DAX** (measures & KPIs)  
- **Star Schema Modeling**

---

## 📌 Conclusion
This Ice Cream Sales Dashboard provides a powerful analytical perspective into how weather, flavor preference, and seasonal patterns affect sales.  
The insights help businesses plan inventory, optimize flavors, schedule promotions, and make smarter business decisions based on real data.

---

## 👤 Author
**Roopesh**  
Power BI | Data Analytics | Business Intelligence  
