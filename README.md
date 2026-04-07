📊 Weekly Earnings Prediction using Regression Analysis


This project focuses on predicting weekly earnings in the US using demographic and job-related variables. The objective was to understand the key drivers of wage variation and build a statistically robust regression model to estimate earnings.

🧩 Problem Statement

Wage prediction is critical for understanding income inequality and labor market trends. This project aims to identify the factors influencing weekly earnings and quantify their impact using regression techniques.

📁 Dataset
Source: Public/academic microwage dataset
Size: ~1.3 million records, 20 features
Final dataset after preprocessing: ~892K records
🛠 Tools & Technologies
Python (pandas, numpy)
Data Visualization (matplotlib, seaborn)
Machine Learning (scikit-learn)
Statistical Modelling (statsmodels)
⚙️ Approach

1. Data Exploration

Analysed distributions and feature relationships
Verified data quality (no missing values)

2. Data Preprocessing

Outlier detection and removal using IQR
Categorical encoding (label encoding & one-hot encoding)

3. Model Development

Built Multiple Linear Regression (OLS model)
Checked multicollinearity using VIF
Refined model by removing weak/high-correlation features

4. Model Validation

Tested assumptions:
Linearity
Homoscedasticity
Normality
Autocorrelation
📈 Key Insights
Age was a significant predictor of weekly earnings, showing a positive relationship with income
Several demographic and job-related features contributed to wage variation
Multicollinearity and heteroscedasticity were identified, indicating real-world data complexity

📊 Model Performance
R² Score: ~0.35
MAE: ~428
RMSE: ~795

👉 The model explains ~35% of income variability, highlighting that earnings are influenced by additional external factors not captured in the dataset.
