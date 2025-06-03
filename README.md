
# 🧠 Analysis on Suicide Trends in India

## 📌 Overview

This project provides a comprehensive analysis of suicide trends in India based on the official **National Crime Records Bureau (NCRB)** data for the year 2021. The main objective is to identify patterns and disparities in suicide rates across different regions — states, cities, and union territories — and present the findings through clear visualizations and exploratory data analysis. The project also introduces basic regression modeling to investigate potential predictive trends.

---

## 🧾 Table of Contents

- [Overview](#-overview)
- [Data Source and Preparation](#-data-source-and-preparation)
- [Project Objectives](#-project-objectives)
- [Key Analyses & Features](#-key-analyses--features)
- [Visualizations](#-visualizations)
- [Regression Modeling](#-regression-modeling)
- [Technologies Used](#-technologies-used)
- [Running the Project](#-running-the-project)
- [Results & Insights](#-results--insights)
- [Collaboration](#-collaboration)
- [Disclaimer](#-disclaimer)

---

## 🗂️ Data Source and Preparation

- **Original Data**: Sourced from the **National Crime Records Bureau (NCRB)**.
- **Scope**: Suicide statistics for the year **2021**.
- **Format**: The original dataset was **manually cleaned and split** into three focused datasets:
  - `state.csv`: Contains suicide data categorized by Indian states.
  - `city.csv`: Contains suicide data categorized by major cities.
  - `union territory.csv`: Contains data for union territories.

All files contain relevant fields such as total number of suicides, region names, and associated metrics.

---

## 🎯 Project Objectives

1. **Identify regional variations** in suicide numbers (state, city, UT).
2. **Highlight regions with extreme values** (highest and lowest suicide counts).
3. **Visualize data** to make patterns easily understandable.
4. **Apply basic regression modeling** to identify trends.
5. **Facilitate better interpretation** of sensitive societal issues through data.

---

## 📊 Key Analyses & Features

- Determination of:
  - State with the highest suicide count
  - State with the lowest suicide count
- Comparative analysis of suicide trends between:
  - States vs UTs
  - Cities vs National average
- Identification of possible socio-geographic factors impacting suicide rates.

---

# Visualizations Used

## Bar Charts

**Distribution of Suicides:**

- States, Union Territories, and Cities (absolute counts).
- Suicide rates per 1000 people (normalized by population).

**Gender-wise Distribution:**

- Stacked bars for Male vs. Female suicides (States, UTs, Cities).

**Predictions for 2024:**

- Bar charts showing projected suicide counts for States, UTs, and Cities.

## Line Charts (Time Series)

**Actual (2021) vs. Predicted (2024) Suicides:**

- Comparative line plots for States, Union Territories, and Cities.

## Annotations

- Numbers inside bars for clarity (counts/rates).
- Rotated x-axis labels (90°) to avoid clutter.

## Color Coding

- Blue: Actual data (2021).
- Red: Predicted data (2024).
- Dodgerblue (Male) vs. Lightcoral (Female): Gender-wise splits.


## 🛠️ Technologies Used

| Technology      | Role in Your Project                                                                 |
|-----------------|-------------------------------------------------------------------------------------|
| **Python**      | The core programming language used to write all analysis scripts and visualizations. |
| **Pandas**      | Used to load, clean, and analyze your suicide data (CSV files) with DataFrames.      |
| **Matplotlib**  | Created all your visualizations (bar charts, line graphs) to show suicide trends.    |
| **Scikit-learn**| Performed simple linear regression to predict future suicide rates (2024 projections).|
| **Google Colab**| The cloud platform where you developed and ran your Jupyter Notebook.                |
---

## 📊 Results & Insights
#### 1. Highest Suicide Rates (2021)
- **State**: Maharashtra (12,207 cases)
- **UT**: Delhi (2,840 cases)  
- **City**: Chennai (1,963 cases)

#### 2. Gender Disparity
- **Male suicides** exceeded female suicides (2:1 ratio)
- **Peak disparity**: Kerala (Male: 5,200 | Female: 2,100)

#### 3. Suicide Rate per 1000
- **Highest**: Kerala (3.2)  
- **Lowest**: Bihar (0.4)

#### 4. 2024 Projections
- **10% annual increase** predicted
- **Top at-risk states**:
  1. Maharashtra (▲14,500)
  2. Tamil Nadu (▲8,200)
  3. West Bengal (▲7,600)

#### Key Insights
1. Urban centers (Delhi, Chennai) show acute crisis
2. Southern states (Kerala, TN) need urgent interventions
3. Male vulnerability remains nationwide concern
4. Growth projections suggest worsening trends
---

## 🤝 Collaboration

- **Team Size**: 2 members
- **Contributions**:
  - Data preprocessing and cleaning
  - Visualization and EDA
  - Regression model development
  - Result interpretation

---

## ⚠️ Disclaimer

This project deals with **real suicide data** and is intended solely for **educational and research purposes**. Suicide is a serious public health issue — any analysis here is intended to support awareness and should be approached with sensitivity.

If you or someone you know is struggling, please seek help from mental health professionals or suicide prevention helplines in your country.

---

