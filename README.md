# 🍷 Wine Quality Data Analysis Project

## 📌 Overview
This project focuses on performing **data cleaning and exploratory data analysis (EDA)** on the Wine Quality dataset.  
The goal is to understand how different chemical properties affect wine quality.

---

## 🎯 Objective
- Clean and preprocess raw data
- Analyze feature distributions
- Identify relationships between variables
- Extract meaningful insights using visualization

---

## 📂 Dataset
- Source: UCI Machine Learning Repository (via Kaggle)
- File: `winequality-red.csv`
- Type: Physicochemical properties of red wine samples

---

## 🛠️ Tools & Libraries Used
- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 🔍 Steps Performed

### 1. Data Loading
- Loaded dataset using Pandas
- Checked structure using `.head()`, `.shape`, `.info()`

### 2. Data Cleaning
- Removed duplicate records
- Verified missing values (none found)

### 3. Exploratory Data Analysis (EDA)
Performed visual analysis on:
- Wine quality distribution
- Correlation between features
- Alcohol vs wine quality
- Density distribution
- Fixed acidity distribution

---

## 📊 Key Visualizations

### 📌 Wine Quality Distribution
Shows how wine ratings are distributed across samples.

### 📌 Correlation Heatmap
Identifies relationships between chemical properties.

### 📌 Alcohol vs Quality
Shows that higher alcohol content tends to correlate with better wine quality.

### 📌 Density & Acidity Distributions
Helps understand data spread and variation.

---

## 💡 Key Insights

- Most wines are rated between 5 and 6.
- Alcohol content has a positive impact on wine quality.
- Some features show weak correlation, indicating independent behavior.
- Dataset is clean and well-structured.
