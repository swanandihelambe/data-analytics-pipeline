# 📊 End-to-End Data Analytics Pipeline

## 📌 Overview
This project demonstrates a complete data analytics workflow using Python, including data cleaning, anonymization, analysis, and visualization.

The dataset contains transaction-level information such as customer details, product categories, purchase amounts, and payment methods.

---

## 🎯 Objective
- Clean and preprocess raw data  
- Apply data anonymization techniques  
- Perform exploratory data analysis  
- Extract meaningful business insights  

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- Matplotlib  

---

## 🔐 Data Anonymization
To ensure data privacy:
- Removed sensitive column: `User_Name`  
- Converted `Age` into grouped categories (`Age_Group`)  
- Preserved analytical value while protecting personal information  

---

## 📊 Analysis Performed
- Monthly sales trend analysis  
- Product category-based sales analysis  
- Payment method distribution  

---

## 📈 Key Insights
- Sales remain relatively stable throughout the year, indicating consistent demand  
- February shows the lowest sales, possibly due to fewer days  
- Mid-year and festive months (July, October, December) show slightly higher sales  
- The business is not heavily dependent on seasonal trends  

---

## 📁 Project Structure
data-analytics-pipeline/
│
├── data/
├── notebook/
│ └── analysis.ipynb
├── visuals/
└── README.md

