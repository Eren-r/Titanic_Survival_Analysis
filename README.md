# 🚢 Titanic Survival Analysis using Exploratory Data Analysis (EDA)

<div align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Analysis-purple)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

</div>

---

# 📊 Overview

This project performs a comprehensive **Exploratory Data Analysis (EDA)** on the famous Titanic dataset to uncover hidden patterns, trends, and factors that influenced passenger survival during the Titanic disaster.

Using Python-based data analysis and visualization techniques, the project explores relationships between passenger demographics, ticket information, socioeconomic status, and survival outcomes.

The goal is to transform raw data into meaningful insights that can support predictive modeling and data-driven decision-making.

---

# 🎯 Problem Statement

The sinking of the Titanic is one of the most well-known maritime disasters in history.

Given passenger information such as age, gender, ticket class, fare, and family size, can we identify the factors that significantly impacted survival rates?

This project aims to answer that question through systematic exploratory data analysis.

---

# ✨ Features

### 📂 Data Exploration

* Dataset Inspection
* Data Types Analysis
* Statistical Summary
* Feature Understanding

---

### 🧹 Data Cleaning

* Missing Value Detection
* Missing Value Treatment
* Duplicate Record Removal
* Data Quality Assessment

---

### 📈 Data Visualization

* Histograms
* Count Plots
* Box Plots
* Correlation Heatmaps
* Survival Analysis Charts

---

### 🔍 Feature Analysis

Analysis of:

* Passenger Class
* Gender
* Age
* Fare
* Family Size
* Embarkation Port

---

### 🛠 Feature Engineering

Created additional features such as:

* Family Size

to better understand passenger behavior and survival probability.

---

# 🧠 EDA Workflow

## 1️⃣ Data Understanding

* Dataset Overview
* Shape Analysis
* Feature Identification
* Data Type Verification

---

## 2️⃣ Data Cleaning

### Missing Values

| Feature  | Action Taken                            |
| -------- | --------------------------------------- |
| Age      | Filled with Median                      |
| Embarked | Filled with Mode                        |
| Cabin    | Removed due to excessive missing values |

---

### Duplicate Records

* Checked and removed duplicate entries where necessary.

---

## 3️⃣ Univariate Analysis

Studied individual features to understand their distributions.

Examples:

* Age Distribution
* Fare Distribution
* Passenger Class Distribution
* Survival Distribution

---

## 4️⃣ Bivariate Analysis

Analyzed relationships between features and survival outcomes.

Examples:

* Gender vs Survival
* Passenger Class vs Survival
* Age vs Survival
* Fare vs Survival

---

## 5️⃣ Multivariate Analysis

Performed advanced relationship analysis using:

* Correlation Matrix
* Heatmaps
* Grouped Aggregations

---

## 6️⃣ Feature Engineering

Generated new feature:

```python
df["FamilySize"] = df["SibSp"] + df["Parch"] + 1
```

This helped analyze the impact of family size on survival rates.

---

# 📈 Key Insights

## 👩 Female Passengers Had Higher Survival Rates

Women were significantly more likely to survive compared to men.

---

## 🏆 First-Class Passengers Were More Likely to Survive

Passengers traveling in first class had a considerably higher survival probability.

---

## 💰 Fare Influenced Survival

Passengers paying higher fares generally experienced better survival outcomes.

---

## 👨‍👩‍👧 Family Size Impacted Survival

Passengers traveling with small families showed higher survival rates.

---

## 👶 Children Had Better Survival Chances

Younger passengers appeared to receive priority during evacuation procedures.

---

# 🛠️ Technology Stack

### Programming Language

* Python

### Data Analysis

* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn

### Development Environment

* Jupyter Notebook

---

# 📊 Sample Visualizations

### Survival Distribution

```python
sns.countplot(x='Survived', data=df)
plt.show()
```

### Gender vs Survival

```python
sns.countplot(x='Sex', hue='Survived', data=df)
plt.show()
```

### Correlation Heatmap

```python
sns.heatmap(df.corr(numeric_only=True), annot=True)
plt.show()
```

---

# 🎓 Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Data Cleaning
* Missing Value Treatment
* Feature Engineering
* Data Visualization
* Statistical Analysis
* Business Insight Generation
* Python Programming
* Pandas & NumPy
* Data Storytelling

---

# 🚀 Future Enhancements

* Build Machine Learning Models for Survival Prediction
* Perform Feature Selection
* Hyperparameter Optimization
* Deploy Prediction Model using Streamlit
* Create Interactive Dashboard
* Compare Multiple Classification Algorithms

---

# 👨‍💻 Developer

**Eren**

Aspiring Data Scientist | AI & Machine Learning Enthusiast

Passionate about transforming raw data into meaningful insights through Data Science, Machine Learning, and Analytics.

---

## ⭐ If you found this project useful, consider giving it a star!

### "Turning Data into Insights, One Dataset at a Time." 🚀📊
