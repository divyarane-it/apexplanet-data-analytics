# 🌧️ Mumbai Monsoon Intelligence
### Rainfall Patterns, Extreme Weather & Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical_Visualization-7DB0D0)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Status](https://img.shields.io/badge/Project-Completed-success)

## 📌 Project Overview

**Mumbai Monsoon Intelligence** is a data analytics project focused on exploring Mumbai's historical rainfall patterns, seasonal distribution, annual variability, and extreme rainfall observations.

Using historical rainfall data covering 1901–2021, this project applies Exploratory Data Analysis (EDA) techniques to identify patterns, trends, anomalies, and seasonal characteristics of rainfall in Mumbai.

The project was developed as part of the **ApexPlanet Data Analytics Internship – Task 1**.

## 🎯 Objectives

- Analyze historical rainfall patterns in Mumbai.
- Understand monthly and seasonal rainfall distribution.
- Identify the wettest and driest years.
- Examine rainfall variability across different decades.
- Analyze extreme monthly rainfall observations.
- Explore relationships between rainfall across different months.
- Visualize rainfall trends and distributions.
- Clean, validate, and prepare the dataset for further analysis.

## 📂 Project Structure

```text
apexplanet-data-analytics/
│
├── data/
│   ├── raw/
│   │   └── original_dataset.csv
│   │
│   └── processed/
│       └── mumbai_rainfall_cleaned.csv
│
├── notebooks/
│   └── Mumbai_Monsoon_Intelligence_EDA.ipynb
│
├── scripts/
├── reports/
├── dashboards/
│
└── README.md
```

## 📊 Dataset Overview

| Attribute | Details |
|---|---|
| Location | Mumbai, Maharashtra, India |
| Data period | 1901–2021 |
| Total records | 121 years |
| Data frequency | Monthly and annual rainfall aggregates |
| Primary analysis | Rainfall patterns and seasonal variability |

### Dataset Variables

- Year
- Monthly rainfall (January–December)
- Total annual rainfall

The dataset also contains derived analytical columns created during the project, including decade classification and seasonal rainfall totals.

> Note: The original dataset source and licensing details should be added once verified.

## 🛠️ Technologies Used

- **Python 3.10**
- **Pandas** – data manipulation and analysis
- **NumPy** – numerical operations
- **Matplotlib** – data visualization
- **Seaborn** – statistical visualization
- **Jupyter Notebook** – interactive analysis environment
- **Git & GitHub** – version control and project hosting

## 🔍 Analysis Performed

### 1. Data Inspection & Quality Assessment
- Dataset structure and dimensions
- Column and data type inspection
- Missing value analysis
- Duplicate record detection
- Numerical statistical summaries

### 2. Data Cleaning & Validation
- Rainfall data type validation
- Negative rainfall value checks
- Annual rainfall total verification against monthly sums
- Dataset consistency checks

### 3. Monthly Rainfall Analysis
- Average rainfall by month
- Monthly rainfall distribution
- Monthly rainfall variability
- Identification of highest monthly rainfall observations

### 4. Annual Rainfall Analysis
- Annual rainfall trends from 1901–2021
- Rainfall distribution histogram
- Annual rainfall boxplot
- Statistical variability analysis

### 5. Extreme Rainfall Analysis
- Identification of the 10 wettest years
- Identification of the 10 driest years
- Detection of statistical outliers using the IQR method
- Extreme monthly rainfall analysis

### 6. Seasonal Analysis
- Monsoon rainfall (June–September)
- Non-monsoon rainfall (January–May and October–December)
- Comparison of average seasonal rainfall
- Percentage contribution of monsoon rainfall to annual totals

### 7. Decadal Analysis
- Average rainfall comparison across decades
- Identification of variations in rainfall between historical periods

### 8. Correlation Analysis
- Monthly rainfall correlation matrix
- Exploration of relationships between rainfall in different months

## 📈 Key Findings

### 🌧️ Annual Rainfall

- Average annual rainfall across the dataset: **2,168.12 mm**
- Wettest year: **2020**, with **3,563.26 mm**
- Driest year: **1941**, with **1,058.84 mm**

### ☔ Seasonal Rainfall Distribution

Mumbai's rainfall is strongly concentrated in the monsoon season.

| Season | Average Rainfall |
|---|---:|
| Monsoon (June–September) | 2,053.75 mm |
| Non-Monsoon | 114.37 mm |

Approximately **94.73%** of average annual rainfall occurs during the four monsoon months.

### 📅 Monthly Rainfall Patterns

- July has the highest average monthly rainfall.
- June, July, August, and September account for the majority of rainfall.
- Rain