# SWYNEX-Exploratory-Data-Analysis_TASK2

# Exploratory Data Analysis (EDA) on Medical Insurance Dataset

This repository contains the code and analysis for Task 2 of my internship at **SWYNEX Technologies**. The goal of this project is to explore a medical insurance dataset to understand the key factors influencing medical charges.

## 📊 Dataset Overview
* **Source:** `insurance.csv`[cite: 1]
* **Attributes (7 columns):** `age`, `sex`, `bmi`, `children`, `smoker`, `region`, and `charges`[cite: 1].
* **Total Records:** 1,338 rows[cite: 1].

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Libraries:** 
  * `pandas` & `numpy` for data manipulation[cite: 1]
  * `matplotlib` & `seaborn` for data visualization[cite: 1]

## 🔍 Key Steps Performed
1. **Data Loading & Inspection:** Loaded the dataset, checked shapes, data types (`info()`), and statistical summaries (`describe()`)[cite: 1].
2. **Data Cleaning:** Verified that there are no missing or null values in the dataset[cite: 1].
3. **Exploratory Data Analysis (EDA):**
   * Plotted distributions of numerical features like `age`, `bmi`, and `charges` using KDE plots and histograms[cite: 1].
   * Analyzed categorical columns like `smoker`, `sex`, and `region` using count plots.
   * Examined correlations to identify primary cost drivers.

## 📈 Insights
* **Smoking Status:** Smokers significantly experience much higher medical charges compared to non-smokers.
* **BMI & Age:** Higher BMI and older age show positive correlations with an increase in individual medical charges.

## 📂 Repository Structure
* `task2_eda.ipynb`: Jupyter notebook containing the full analysis and code.
* `insurance.csv`: The dataset used for the analysis[cite: 1].

---
*Developed by Chetan Rathore*
