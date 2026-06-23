# 🏠 Housing Price Prediction

## 📌 Project Overview

This project predicts housing prices using Machine Learning techniques. The workflow includes data cleaning, exploratory data analysis (EDA), feature engineering, model training, hyperparameter tuning, and evaluation.

The goal is to identify the key factors affecting house prices and build a predictive model capable of estimating property values accurately.

---

## 📊 Dataset Features

The dataset contains housing-related information such as:

- Longitude
- Latitude
- Housing Median Age
- Total Rooms
- Total Bedrooms
- Population
- Households
- Median Income
- Ocean Proximity
- Median House Value (Target)

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## 📈 Exploratory Data Analysis

Performed:

- Missing value analysis
- Correlation heatmaps
- Pairplots
- Scatterplots
- Geographical analysis using latitude and longitude

---

## ⚙️ Feature Engineering

### Log Transformation

Applied logarithmic transformation to:

- Total Rooms
- Total Bedrooms
- Population
- Households

### New Features

Created:

- Bedroom Ratio
- Household Rooms Ratio

### Encoding

Applied One-Hot Encoding on:

- Ocean Proximity

### Scaling

Used:

```python
StandardScaler()
