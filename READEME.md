# Sales Performance Analysis - EDA

## 📌 Project Overview  
This project is an **Exploratory Data Analysis (EDA)** on a sales dataset.  
The goal is to analyze sales performance across different dimensions such as **products, countries, cities, and time periods**, and to extract meaningful insights that could help businesses improve their strategies.

---

## 🗂 Dataset  
- Source: CSV file (`all_data.csv`)  
- Key columns include:  
  - `OrderDate` → Order transaction date  
  - `Country` / `City` → Customer location  
  - `Product`, `UnitPrice`, `Quantity`  
  - `TotalAmount` → Order revenue  

---

## 🔍 Analysis Steps  
1. **Data Loading & Cleaning**  
   - Standardized column names  
   - Converted `OrderDate` into datetime format  
   - Fixed data types for IDs and numeric values  
   - Handled missing values  

2. **Descriptive Statistics**  
   - Summary statistics for sales amounts and prices  
   - Distribution plots (Histograms, Boxplots)  
   - Outlier detection using IQR method  

3. **Geographical Analysis**  
   - Orders by city and country  
   - Bar charts and pie charts for distribution  

4. **Time Series Analysis**  
   - Monthly trends in orders and countries involved  
   - Line charts to identify peaks and seasonality  

---

## 📊 Tools & Libraries  
- **Python**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn, Plotly 

---

## 📈 Key Insights
- Identified top-performing countries and cities in sales.
- Found sales seasonality by analyzing monthly order trends.
- Highlighted outliers in prices and revenues.