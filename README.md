# 📈 UK Employment & Pay Analytics using Machine Learning

## Overview

This project investigates the relationship between employment levels and average salaries across UK industries using machine learning techniques.

The objective was to explore sector-level employment trends, preprocess real-world payroll data, build predictive models, and evaluate how accurately employment data can forecast average salaries.

---

## Project Objectives

- Explore relationships between employment and average pay
- Perform exploratory data analysis (EDA)
- Handle missing values and prepare the dataset for modelling
- Compare multiple machine learning algorithms
- Evaluate predictive performance using regression metrics
- Identify patterns through unsupervised learning

---

## Dataset

The project uses UK employment and average pay datasets covering multiple industry sectors over time.

The datasets include:

- Industry employment counts
- Mean monthly pay
- Payroll quality indicators
- Regional payroll information

---

## Machine Learning Pipeline

### 1. Data Exploration

- Summary statistics
- Correlation analysis
- Industry comparisons
- Trend analysis

### 2. Data Preprocessing

- Missing value imputation
- Feature engineering
- Data transformation
- Standardisation

### 3. Supervised Learning

Implemented:

- Linear Regression
- Random Forest Regressor

Models were evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

### 4. Unsupervised Learning

Implemented:

- K-Means Clustering

Cluster quality evaluated using:

- Elbow Method
- Silhouette Score

---

## Results

The analysis showed that:

- Employment and average pay exhibit strong positive relationships in several industries.
- Linear Regression outperformed Random Forest on this dataset.
- The relationship between employment and salary is largely linear at this level of aggregation.
- K-Means clustering identified four meaningful groups of industries with similar employment-pay characteristics.

---

## Technologies

- Python
- pandas
- NumPy
- scikit-learn
- Matplotlib
- Seaborn
- SciPy
- Missingno

---

## Future Improvements

Possible extensions include:

- Time-series forecasting using ARIMA or LSTM
- Additional macroeconomic variables (GDP, inflation, unemployment)
- XGBoost and LightGBM models
- Interactive dashboard for model exploration
- Model deployment as a web application

---

## Skills Demonstrated

- Machine Learning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Cleaning
- Data Visualisation
- Regression Modelling
- Clustering
- Model Evaluation
- Python Programming
