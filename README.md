# House-Price-Prediction
---

## 📌 Overview

This project focuses on **analyzing housing data to validate the core assumptions of Linear Regression** before building a predictive model for **house price estimation**.
The objective is to ensure that the dataset satisfies statistical requirements such as **linearity, normality, absence of multicollinearity, and minimal outliers**, which are essential for building an interpretable and reliable regression model.

Through **exploratory data analysis (EDA)** and **assumption testing**, the project identifies data quality issues and highlights areas requiring transformation or optimization. This structured approach mirrors **real-world data science workflows**, where validating assumptions is a critical step before model deployment.

---

## 🗂️ Dataset

The dataset (`Houses.xlsx`) contains **numerical housing attributes** that influence property prices.
Each row represents an individual house, and each column captures a specific characteristic affecting valuation.

### 🎯 Target Variable

* **`price`** – Market price of the house (continuous numerical variable)

### 📊 Independent Variables

* **`bedrooms`** – Number of bedrooms in the house
* **`bathrooms`** – Number of bathrooms
* **`age_years`** – Age of the property in years
* **`distance_city_center_km`** – Distance from the city center (in kilometers)
* **`num_schools_nearby`** – Number of schools within close proximity
* **`crime_rate_index`** – Crime index of the surrounding area

### 🔍 Dataset Characteristics

* All variables are **numerical**
* No categorical encoding required
* Contains some **outliers and skewed distributions**
* Suitable for **regression analysis after preprocessing**



Just say the word 👍
