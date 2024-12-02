## 🚀 Overview
This repository features a **Diamond Sales Prediction System**, leveraging **machine learning** and **deep learning** to predict the total sales price of diamonds based on key attributes like carat weight, cut, clarity, and more.

## 🌟 Features
1. **Dataset**:
   - Includes diamond attributes such as `cut`, `color`, `clarity`, `carat weight`, and `total sales price`.
   - Dataset size: **219,703 records**.

2. **Data Preprocessing**:
   - Removed duplicate rows.
   - Handled outliers in measurement dimensions (`meas_length`, `meas_width`, `meas_depth`) by capping extreme values and filtering zero values.

3. **Modeling**:
   - **Machine Learning Models**: Implemented Random Forest and Linear Regression.
     
4. **Evaluation**:
   - Achieved **Mean Squared Error (MSE)** of 1.89e+08 on the test data for the neural network model.
   - Visualization of predictions against actual values for insights.

⚙️ **Workflow**

**Data Cleaning**:

- Identified and removed duplicate rows.

- Addressed missing values using mean imputation.
- Filtered extreme outliers using interquartile range (IQR).
- Exploratory Data Analysis (EDA):
- Visualized correlations with a heatmap.
- Examined feature distributions using scatter plots for attributes like carat_weight, meas_length, and meas_width.

**Feature Selection**:

- Selected high-correlation features for model input.
- Used carat_weight, cut_quality, clarity, color, and measurement parameters.

**Model Building**:

- Built Random Forest and Linear Regression models for baseline predictions.

**Evaluation**:

- Compared model performance using Mean Squared Error (MSE).
- Visualized the predicted vs. actual sales for insights.

📊 **Results**

- Random Forest: MSE = 2.10e+08

