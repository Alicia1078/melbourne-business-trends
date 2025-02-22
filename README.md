# 📊 Melbourne Business Trends Analysis (2002-2022)

## 📖 Overview
This project analyzes **business establishment trends in Melbourne** over a 20-year period (2002-2022).  
Using **R and statistical methods**, the study examines economic changes across different industries and predicts future trends in business distribution.  

## 🔍 Key Objectives
✅ Analyze **business growth and decline** across Melbourne using government datasets.  
✅ Identify **patterns and clusters** in business establishment distribution.  
✅ Predict **future industry trends** using **time-series forecasting models**.  

---

## 📂 Dataset
📌 **Source**: [City of Melbourne Open Data](https://data.melbourne.vic.gov.au/)  
- **Dataset**: Business Establishments per Block by ANZSIC (2002-2022)  
- Covers business distribution across different Melbourne regions.  

---

## 🛠️ Methods & Tools

### **🛠 R Packages Used**
- **Data Processing & Cleaning**: `tidyverse`, `readxl`, `dplyr`
- **Visualization**: `ggplot2`
- **Clustering Analysis**: `factoextra`, `cluster`
- **Time-Series Forecasting**: `forecast`, `tseries`, `auto.arima`

### **📊 Analytical Approaches**
1. **Data Cleaning & Preprocessing**
   - Removed unnecessary columns and cleaned missing data.
   - Aggregated business establishment counts by region and year.

2. **Business Growth Trends Analysis**
   - Identified **CBD vs Non-CBD** trends.
   - Plotted business growth trends before and after COVID-19.

3. **Clustering Analysis**
   - Used **K-Means and Hierarchical Clustering** to identify **similar business regions**.
   - Categorized Melbourne into **three main clusters** based on business density and type.

4. **Time-Series Forecasting**
   - Applied **ARIMA, ETS, and Linear Regression models**.
   - Predicted **future business trends** for the next 5 years.

---

## 📊 Key Findings

### **📈 Business Growth Trends**
- **Melbourne CBD consistently dominates** in business establishment numbers.
- **Significant decline post-2020**, likely due to **COVID-19's impact** on businesses.

### **📍 Business Clustering**
- **Cluster 1**: Mixed-use areas with moderate business activity.
- **Cluster 2**: Residential & institutional zones with fewer commercial businesses.
- **Cluster 3**: High-density business districts (**Melbourne CBD**).

### **📉 Industry Distribution Changes**
- 📉 **Industrial sector** declined from **15.5% (2002) to 10.95% (2022)**.
- 📈 **Entertainment sector** increased from **16.48% to 24.88%**.
- 📉 **Commercial sector** declined slightly from **44.44% to 39.71%**.

### **🔮 Future Predictions (2023-2028)**
- 📉 **Retail & Industrial sectors** expected to continue **declining**.
- 📈 **Entertainment & Institutional sectors** expected to **grow**.
- 📈 **Commercial businesses** may **recover** slightly after recent declines.
- **Auto.ARIMA model provided the most reliable forecasts**.

---

## 🚀 How to Run This Project

1. **Clone the repository**:
   ```bash
   git clone git@github.com:Alicia1078/melbourne-business-trends.git
   cd melbourne-business-trends
