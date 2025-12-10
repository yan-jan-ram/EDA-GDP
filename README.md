<!-- PROJECT BADGES -->
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Language](https://img.shields.io/badge/Built%20With-Python-blue?logo=python)
![Notebook](https://img.shields.io/badge/Environment-Jupyter-orange?logo=jupyter)
![Libraries](https://img.shields.io/badge/Libraries-Pandas%20%7C%20NumPy%20%7C%20Matplotlib%20%7C%20Seaborn-purple)
![Dataset](https://img.shields.io/badge/Source-Our%20World%20In%20Data-red)

# 🌍 EDA – Global GDP Analysis (1990–2023)

A complete **Exploratory Data Analysis (EDA)** of world GDP per capita data sourced from **Our World in Data (World Bank 2025 update)**.  
This analysis uncovers global economic patterns, long-term income trends, high-growth regions, and cross-country comparisons over the last three decades.

This project demonstrates strong competence in:  
✔ Data cleaning  
✔ Exploratory analysis  
✔ Visualization  
✔ Insight extraction  
✔ Python (Pandas, NumPy, Matplotlib, Seaborn)

---

## 📌 Project Overview

The objective of this project is to analyze how **GDP per capita** has changed around the world from **1990 to 2023**, and identify:

- Countries with rapid economic growth  
- Stagnant or declining economies  
- Comparative GDP trends across continents  
- Global inequality patterns  
- Volatility in developing regions  

This is a pure **Python analytics project**, executed in **Jupyter Notebook**.

---

## 🧠 Key Skills Demonstrated

### ✔ Data Cleaning & Preparation  
- Handling missing values  
- Filtering by selected regions/countries  
- Fixing inconsistent formats  
- Loading and merging CSV + JSON metadata  

### ✔ Exploratory Data Analysis  
- Trend analysis over multiple decades  
- Top/bottom country comparisons  
- Year-over-year growth patterns  
- Economic variance & volatility analysis  

### ✔ Visualizations (Matplotlib + Seaborn)  
- Global GDP trend line charts  
- Top-10 GDP per capita countries  
- Distribution & histogram plots  
- Correlation heatmaps  
- Multi-country comparison time-series graphs  

---

## 📊 Sample Visuals (Add screenshots into /plots folder)

```md
![GDP Trend](plots/gdp_trend.png)
![Top 10 Countries](plots/top10_countries.png)
![GDP Distribution](plots/global_distribution.png)
```

## 📂 Project Structure
```DAX
EDA-GDP/
│
├── data/
│   ├── gdp_per_capita.csv        # Main dataset
│   └── metadata.json             # Source metadata
│
├── notebooks/
│   └── EDA_GDP.ipynb             # Main analysis
│
├── plots/
│   ├── gdp_trend.png
│   ├── top10_countries.png
│   └── global_distribution.png
│
└── README.md
```

## 🔍 Insights & Findings
### 🌎 Global Trends

- GDP per capita has steadily increased worldwide, with especially strong growth in East Asia.
- High-income countries like Luxembourg, Switzerland, Norway, Singapore consistently top the global ranking.

### 📉 Countries with Declining or Volatile GDP

- Conflict-affected and low-income regions show inconsistent or negative trends.
- Some economies exhibited sharp volatility due to political or economic crises.

### 📈 High-Growth Economies

- Countries with the most significant long-term GDP growth include:
- China, India, Vietnam, Bangladesh, Poland, Estonia, and others.

## 📘 About the Dataset

- Source: Our World in Data – GDP per capita (constant 2021 international-$)
- Dataset Range: 1990–2023
- Unit: International dollars (PPP-adjusted)
- Columns: Entity, Code, Year, GDP per capita
