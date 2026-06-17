# Crimes Against Women in India: Exploratory Data Analysis (EDA)

## 📌 Project Overview

Crimes against women remain a significant social issue in India, with different states exhibiting varying crime patterns and trends over time. This project performs an end-to-end Exploratory Data Analysis (EDA) on state-wise crime data to identify high-risk regions, analyze temporal trends, and generate data-driven insights that can support policy-making and social awareness initiatives.

---

## 🎯 Objectives

* Analyze state-wise distribution of crimes against women.
* Identify states with the highest crime volumes.
* Study year-wise trends and changes in crime patterns.
* Determine the most prevalent crime categories.
* Explore relationships between different crime types.
* Generate actionable insights through data visualization.

---

## 📂 Dataset Information

**Dataset Name:** Crimes Against Women in India

**Time Period:** 2001 – 2021

**Features:**

| Column | Description                    |
| ------ | ------------------------------ |
| State  | State/UT Name                  |
| Year   | Reporting Year                 |
| Rape   | Number of Rape Cases           |
| K&A    | Kidnapping and Abduction Cases |
| DD     | Dowry Death Cases              |
| AoW    | Assault on Women               |
| AoM    | Insult to Modesty of Women     |
| DV     | Domestic Violence Cases        |
| WT     | Women Trafficking Cases        |

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Git & GitHub

---

## 🔄 Project Workflow

### 1. Data Loading

* Imported dataset using Pandas.

### 2. Data Understanding

* Dataset shape
* Data types
* Statistical summary
* Unique states and years

### 3. Data Cleaning

* Checked for missing values
* Checked duplicate records
* Standardized state names
* Verified data consistency

### 4. Feature Engineering

Created:

* Total_Crimes
* Year-over-Year (YoY) Growth (optional)

### 5. Exploratory Data Analysis (EDA)

Performed analysis on:

* State-wise total crimes
* Year-wise crime trends
* Top states with highest crimes
* Crime category distribution
* Correlation analysis
* State vs Year heatmap
* Trend analysis of major states

---

## 📊 Key Visualizations

* Top 10 States by Total Crimes
* Year-wise Crime Trend
* Crime Category Distribution
* Correlation Heatmap
* State vs Year Heatmap
* State Trend Analysis

---

## 🔍 Key Insights

* Uttar Pradesh, Madhya Pradesh, Rajasthan, and West Bengal consistently report high crime volumes.
* Domestic violence and assault-related crimes contribute significantly to total crimes.
* Certain states exhibit increasing crime trends over time.
* Crime patterns vary substantially across states and years.
* Multiple crime categories show positive correlations.

---

## ⚠️ Limitations

* Analysis is based on absolute crime counts and does not account for population differences across states.
* Changes in reporting mechanisms and legal definitions over time may influence observed trends.
* Higher reported crime counts do not necessarily indicate lower safety; they may also reflect better reporting practices.

---

## ✅ Conclusion

This project demonstrates how Exploratory Data Analysis can be used to uncover patterns and trends in crimes against women across India. The analysis highlights high-risk regions, major crime categories, and temporal changes, providing insights that may assist policymakers, researchers, and social organizations in understanding the issue more effectively.

---

## 🚀 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Data Visualization
* Statistical Analysis
* Business Insight Generation
* Data Storytelling
* Git & GitHub

---

## 📁 Repository Structure

```text
Crimes-Against-Women-in-India-EDA/
│
├── data/
│   └── CrimesOnWomenData.csv
│
├── notebooks/
│   └── Crimes_Against_Women_India_EDA.ipynb
│
├── images/
│   ├── top_states.png
│   ├── yearly_trend.png
│   ├── correlation_heatmap.png
│   └── state_year_heatmap.png
│
├── README.md

```

---

## 👤 Author

Yash Kagra

B.Tech CSE | Data Science & Analytics Enthusiast

Skills: Python, SQL, Excel, Pandas, NumPy, Matplotlib, Seaborn, Machine Learning
