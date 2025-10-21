# 📊 Sales Analysis Dashboard — Power BI Project

## 🧠 Project Overview
This project presents an **interactive Power BI dashboard** designed to analyze sales performance across multiple regions, time periods, and product categories.  
The goal is to help stakeholders **monitor key metrics, identify trends, and compare performance** through data visualization and DAX-powered insights.

---

## 🗂️ Data Modeling
Data modeling was performed to create a **normalized star schema**, connecting dimension and fact tables such as:
- **Customers**
- **Products**
- **Sales**
- **OrderDate**
- **SalesTerritories**

Relationships were built between these tables to support **accurate aggregations** and efficient DAX calculations.

---

## ⚙️ DAX Measures
Custom **DAX measures** were created to calculate key KPIs, including:
- **Total Sales**
- **Target**
- **Average Revenue**
- **Total Margin**
- **Total Price**
- **Year-to-Date (YTD) Sales**
- **Quarter-to-Date (QTD) Sales**

These measures power the visuals and enable interactive filtering by **Year**, **Quarter**, and **Country**.

---

## 📈 Dashboard Pages & Visuals

### **Page 1 — Sales Overview**
- **Donut Chart:** Total Sales by Continent  
- **Line & Column Chart:** Total and Average Revenue by Country  
- **Area Chart:** Total Revenue by Quarter  
- **Ribbon Chart:** Total Revenue by Product Category and Region  
- **Cards:** Total Sales, Average Revenue, Total Margin, and YTD Sales  
- **Slicers:** Quarter, Year, and Country  

### **Page 2 — Sales Details**
- **Treemap:** Total Revenue by Region  
- **Column & Line Chart:** Total and Average Revenue by Month  
- **Table:** Monthly breakdown of YTD, QTD, and Total Sales for each year  

---

## 💡 Insights
- North America leads in total sales, followed by Australia and Europe.  
- Revenue peaks in **Q1 and Q2**, with a decline in later quarters.  
- **May and June** consistently record the highest monthly revenues.  
- Product category performance varies significantly by region.

---

## 🧰 Tools & Technologies
- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query Editor** (for data cleaning and transformation)
- **Data Modeling**

---

## 🚀 How to Use
1. Download the `.pbix` file from this repository.  
2. Open it using **Power BI Desktop**.  
3. Use the slicers (Year, Quarter, Country) to explore data interactively.  

---

## 📷 Dashboard Preview

### **Sales Overview**
![Sales Overview](images/Sales%201.PNG)


### **Sales Details**
![Sales Details](images/Sales%202.PNG)

---

## 🏁 Conclusion
This project demonstrates how **data modeling and DAX** can transform raw sales data into meaningful insights through interactive visual storytelling in Power BI.




