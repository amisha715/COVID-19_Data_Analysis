
# 📊 COVID-19 Data Analysis using Python

## 📌 Overview
This project performs Exploratory Data Analysis (EDA) on COVID-19 data to understand the spread of the virus and its relationship with socio-economic factors like GDP and social support.

---

## 🎯 Objectives
- Analyze COVID-19 trends across countries  
- Convert cumulative data into daily cases  
- Identify peak infection rates  
- Study correlation with economic indicators  

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 📂 Datasets
- COVID-19 Confirmed Cases Dataset  
- Worldwide Happiness Report  

---

## 🔍 Workflow
1. Data Loading and Inspection  
2. Data Cleaning (removing unnecessary columns)  
3. Aggregation using groupby (country-level data)  
4. Time-series transformation using `.diff()`  
5. Feature Engineering (max infection rate)  
6. Data Merging (COVID + Happiness dataset)  
7. Correlation Analysis  
8. Data Visualization  

---

## 📈 Key Insights
- Higher GDP countries show higher reported infection rates  
- Testing and reporting differences may influence results  
- Socio-economic factors impact pandemic trends  

---

## ⚠️ Limitations
- Possible data bias  
- Limited variables considered  
- No time-lag analysis  

---

## 🚀 How to Run
```bash
git clone https://github.com/amisha715/COVID19_Data_Analysis.git
cd COVID19_Data_Analysis
pip install pandas numpy matplotlib seaborn
jupyter notebook
