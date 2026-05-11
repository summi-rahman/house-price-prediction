````markdown
# California Housing Price Prediction using Machine Learning

## Project Overview

This project focuses on predicting California housing prices using Machine Learning techniques and the California Housing Dataset from Scikit-learn. The project follows a complete end-to-end Machine Learning workflow including data preprocessing, Exploratory Data Analysis (EDA), feature engineering, model building, prediction, and evaluation.

The main objective of this project is to understand how different housing-related features such as average rooms, income, population, house age, and geographical location influence house prices.

---

# Machine Learning Theory

## What is Machine Learning?

Machine Learning is a branch of Artificial Intelligence that enables systems to learn patterns from data and make predictions without being explicitly programmed.

This project uses:

- Supervised Learning
- Regression Analysis

because the target variable (house price) is continuous.

---

# What is Regression?

Regression is a Machine Learning technique used to predict continuous numerical values.

Examples:
- House price prediction
- Stock price prediction
- Sales forecasting

In this project, the model predicts:

```python
MedHouseVal
```

which represents the median house value.

---

# Linear Regression Theory

The project uses the Linear Regression algorithm.

Linear Regression tries to find the best-fit line between input features and the target variable.

Mathematical Equation:

\[
y = mx + b
\]

Where:
- \( y \) = predicted value
- \( x \) = input feature
- \( m \) = slope/coefficient
- \( b \) = intercept

The algorithm minimizes prediction error using optimization techniques.

---

# Exploratory Data Analysis (EDA)

EDA is the process of analyzing and understanding the dataset before model building.

EDA performed in this project includes:

- Dataset overview
- Missing value analysis
- Duplicate analysis
- Statistical summary
- Correlation analysis
- Distribution plots
- Scatter plots
- Boxplots
- Pairplots
- Skewness analysis

EDA helps identify:
- patterns
- relationships
- outliers
- important features

---

# Missing Value Handling Theory

Missing values are handled using skewness-based imputation logic.

## Numerical Features

- Symmetric data → Mean
- Skewed data → Median

## Categorical Features

- Mode is used

This improves data quality and model performance.

---

# Feature Engineering

Feature engineering is the process of creating or selecting meaningful features to improve Machine Learning performance.

In this project:
- Important housing-related features were selected
- Additional derived features were created

Example:
```python
RoomsPerPerson
```

---

# Model Evaluation Metrics

The model was evaluated using:

## Mean Absolute Error (MAE)

Measures average prediction error.

Lower MAE is better.

---

## Mean Squared Error (MSE)

Penalizes large prediction errors.

Lower MSE is better.

---

## Root Mean Squared Error (RMSE)

Square root of MSE.

Provides interpretable error values.

Lower RMSE is better.

---

## R² Score

Measures how well the model explains variance in the data.

Range:
- 0 → Poor model
- 1 → Perfect model

Higher R² is better.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Understanding
4. Missing Value Analysis
5. Missing Value Handling
6. Exploratory Data Analysis
7. Feature Engineering
8. Train-Test Split
9. Model Building
10. Prediction
11. Model Evaluation
12. Visualization

---

# Dataset

Dataset Used:
- California Housing Dataset from Scikit-learn

Dataset Features:
- Median Income
- House Age
- Average Rooms
- Average Bedrooms
- Population
- Occupancy
- Latitude
- Longitude

Target Variable:
```python
MedHouseVal
```

---

# Conclusion

This project demonstrates a complete Machine Learning workflow for regression problems using Python and Scikit-learn. It provides practical experience in data preprocessing, EDA, feature engineering, regression modeling, and evaluation, which are essential concepts in Data Science and Machine Learning.

````
