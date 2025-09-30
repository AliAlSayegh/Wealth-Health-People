# 🌍 Wealth, Health, and Population

## 📖 Overview
This project explores the relationship between **wealth (GNI per capita)**, **health (life expectancy)**, and **population dynamics** across countries from **1800 to 2100**.  
Using Python, Pandas, and Seaborn, the analysis highlights global trends, inequalities, and projections that shape our understanding of human development.

---

## 🎯 Objectives
- Analyze the **correlation between wealth, health, and population**.  
- Identify **top and bottom performing countries** across different years.  
- Examine **trends and disparities** in global development.  
- Provide **visual insights** using statistical charts and plots.  

---

## 📂 Dataset
The analysis is based on three datasets with the same structure:

- `gni_per_cap_atlas_method_con2021.csv` → Gross National Income per capita  
- `life_expectancy.csv` → Average life expectancy (years)  
- `population.csv` → Total population  

Each dataset contains:
- **Columns:** `['country', '1800', '1801', ..., '2100']`  
- **Rows:** Countries worldwide  

---

## 🛠️ Technologies Used
- **Python 3.11+**
- **Jupyter Notebook**
- **Pandas** → Data manipulation  
- **NumPy** → Numerical operations  
- **Seaborn & Matplotlib** → Data visualization  

---

## 📊 Features & Analysis
- 📈 **Trend Analysis** → Changes in GNI, life expectancy, and population over time.  
- 🌍 **Country-Specific Analysis** → Subplots comparing indicators for selected countries.  
- 🔝 **Top 10 Rankings** → Countries with the highest values in each category.  
- 📉 **Lowest Rankings** → Countries with the lowest values in each category.  
- 📊 **Rate of Change** → Countries with the fastest/slowest growth over time.  
- 📌 **Comparisons**:
  - GNI per capita vs. Life Expectancy  
  - Life Expectancy vs. Population  
  - Population vs. GNI per capita  

---

## 📑 Project Structure
Wealth-Health-Population/
│── data/
│ ├── gni_per_cap_atlas_method_con2021.csv
│ ├── life_expectancy.csv
│ ├── population.csv
│
│── main_analysis.ipynb
│
│── README.md
