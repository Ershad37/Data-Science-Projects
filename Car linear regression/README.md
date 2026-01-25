# Car Price Prediction and Analysis

This project analyzes car price data and builds a **linear regression model** to predict car prices based on features like **Year**, **Engine Size**, and **Mileage**. It also provides visualizations to understand the relationships between these features and car price.

---

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Methodology](#methodology)
- [Visualizations](#visualizations)
- [Regression Results](#regression-results)
- [License](#license)

---

## Overview
The goal of this project is to explore how car attributes affect the selling price and to predict car prices using linear regression. We perform the following tasks:
1. Load and inspect the dataset.
2. Check for missing values.
3. Define independent variables (features) and dependent variable (target).
4. Fit a linear regression model.
5. Predict prices and visualize relationships.

---

## Dataset
The dataset used in this project is `Car_Price_Prediction.csv`.  
It contains information about various cars, including:

- `Year`: Manufacturing year of the car
- `Engine Size`: Size of the car engine
- `Mileage`: Distance the car has traveled
- `Price`: Selling price of the car (target variable)

---

## Dependencies
The project requires the following Python libraries:

- `pandas` – for data manipulation
- `matplotlib` – for plotting
- `seaborn` – for advanced visualizations
- `statsmodels` – for linear regression modeling

Install dependencies using pip:

```bash
pip install pandas matplotlib seaborn statsmodels
