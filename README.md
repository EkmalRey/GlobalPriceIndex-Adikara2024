# Predicting Food Price Index Using Linear Regression

This project implements **Linear Regression** to predict the **Food Price Index (FPI)** based on temporal data (year and month). It compares various predictive models and data imputation methods to achieve robust predictions.

---

### Table of Contents

- [Predicting Food Price Index Using Linear Regression](#predicting-food-price-index-using-linear-regression)
    - [Table of Contents](#table-of-contents)
    - [Introduction](#introduction)
    - [Objectives](#objectives)
    - [Features and Methods](#features-and-methods)
    - [Results and Insights](#results-and-insights)
    - [Contributors](#contributors)

---

### Introduction

Fluctuations in food prices significantly impact global economic stability, food security, and societal welfare. This study explores:
- Using **Linear Regression** for predictive modeling of the Food Price Index.
- Effective handling of **missing values** via regression-based imputation.
- Excluding categorical features, like *Country*, for improved model generalization.

---

### Objectives

The project's objectives include:
1. Performing **Exploratory Data Analysis (EDA)** to understand patterns in the dataset.
2. Handling missing data using:
   - Data deletion.
   - Linear interpolation.
   - Regression-based imputation.
3. Building and evaluating models like **Linear Regression**, **Decision Tree**, and more.
4. Validating the removal of the *Country* feature to improve unseen data performance.

---

### Features and Methods

- **EDA Insights**: Examines temporal trends and data distributions.
- **Missing Value Handling**: Regression-based imputation demonstrated the highest correlation with target variables.
- **Feature Selection**: Temporal features (*Year* and *Month*) optimized model performance. Removing the *Country* feature reduced overfitting.
- **Model Comparison**: Evaluated six models with **Linear Regression** emerging as the best performer.

---

### Results and Insights

- **Best Performing Model**: Linear Regression achieved:
  - Mean Squared Error (MSE): **298.52**
  - R² Score: **0.65**
- **Imputation Methods**: Regression-based imputation outperformed interpolation and data deletion.
- **Feature Engineering**: Excluding *Country* enhanced generalization.

---

### Contributors

- **Ekmal Reyhan Tarihoran**  
- **Hafizh Putra Ardhana**  
- **Farrell Habibie Putra Haris**

Faculty of Informatics, Telkom University, 2024.