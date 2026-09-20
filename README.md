# 🚗 Global Cars Enhanced Analysis

## 📌 Project Overview

**Global Cars Enhanced Analysis** is a Python-based Exploratory Data Analysis (EDA) project that analyzes a dataset of cars from different brands, manufacturing countries, fuel types, body types, transmission methods, performance specifications, prices, and efficiency measures.

The project focuses on understanding patterns in the global automobile dataset through **data cleaning, statistical analysis, grouping, and data visualization**.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Analyze car brands and their distribution.
* Study car manufacturing years.
* Analyze different body types.
* Compare fuel types.
* Analyze transmission methods.
* Explore engine capacity and horsepower.
* Analyze mileage and efficiency.
* Study car prices and price categories.
* Compare manufacturing countries.
* Analyze car age categories.
* Identify the most expensive car.
* Identify cars with the highest horsepower-to-engine-capacity ratio.
* Perform grouping and aggregation using Pandas.
* Create meaningful visualizations from the dataset.

---

## 📊 Dataset

The dataset contains **300 car records and 16 columns**.

### Dataset Features

| Column                  | Description                            |
| ----------------------- | -------------------------------------- |
| `Car_ID`                | Unique identifier for each car         |
| `Brand`                 | Car manufacturer/brand                 |
| `Manufacture_Year`      | Year the car was manufactured          |
| `Body_Type`             | Type of car body                       |
| `Fuel_Type`             | Fuel used by the car                   |
| `Transmission`          | Manual or automatic transmission       |
| `Engine_CC`             | Engine capacity in cubic centimeters   |
| `Horsepower`            | Engine horsepower                      |
| `Mileage_km_per_l`      | Mileage in kilometers per litre        |
| `Price_USD`             | Car price in USD                       |
| `Manufacturing_Country` | Country where the car was manufactured |
| `Car_Age`               | Age of the car                         |
| `Price_Category`        | Budget, Mid-Range, Premium, or Luxury  |
| `HP_per_CC`             | Horsepower per engine CC               |
| `Age_Category`          | Category based on car age              |
| `Efficiency_Score`      | Overall efficiency score               |

---

## 🛠️ Technologies Used

* 🐍 Python
* 🐼 Pandas
* 🔢 NumPy
* 📊 Matplotlib
* 📓 Jupyter Notebook

---

## 🔍 Data Cleaning

The project begins with basic data-quality checks.

### Dataset Size

```text
300 rows × 16 columns
```

### Missing Values

The dataset contains **no missing values** across the analyzed columns.

### Duplicate Check

`Car_ID` was checked for duplicate values, and no duplicate IDs were identified.

### Data Types

The dataset contains:

* **8 object/categorical columns**
* **6 integer columns**
* **2 floating-point columns**

---

# 📈 Exploratory Data Analysis

## 1. 🚘 Car Brand Distribution

The analysis contains 10 car brands:

| Brand  | Count |
| ------ | ----: |
| Nissan |    41 |
| Tesla  |    35 |
| For    |       |
