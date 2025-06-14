# 💎 Diamond Price Prediction Using Machine Learning
This project aims to build a machine learning model to accurately predict the price of diamonds based on key features like carat, cut, color, clarity, depth, and table. It includes complete data preprocessing, exploratory data analysis, model building, and evaluation — all implemented using custom Python code.

## 📌 Project Overview
Objective: Predict diamond prices to assist buyers, sellers, and traders in fair valuation.

Dataset: ~54,000 diamond records from Seaborn’s dataset.

Target Variable: price (in US dollars)

Tools & Libraries: pandas, matplotlib, seaborn, scikit-learn

## 🧠 Features Used
Feature	Description:

          carat:	Weight of the diamond
          cut: Quality of cut (Fair, Good, Very Good, Premium, Ideal)
          color: 	Diamond color grading (D to J)
          clarity: 	Diamond clarity level
          depth:	Depth percentage
          table:	Table width percentage
          price:	Target variable (USD)

❌ Dropped features: x, y, z (Highly correlated with carat — removed to reduce multicollinearity)

## 🔍 Exploratory Data Analysis
✅ Univariate Analysis
Histograms plotted to understand distribution of carat, depth, table, price

✅ Bivariate Analysis
Scatterplots used to identify relationships with target variable (carat vs price, etc.)

✅ Multivariate Analysis
Correlation heatmap helped identify highly correlated features and guided feature selection

✅ Outlier Detection
Box plots revealed outliers in carat, price, etc., aiding data cleaning

## 🧹 Data Preprocessing
Dropped Unnamed: 0 column

Handled corrupted values in x, y, z

Categorical encoding using LabelEncoder for cut, color, and clarity

Removed x, y, z due to multicollinearity

## 🤖 Models Implemented
Model	R² Score
Linear Regression	0.91 ✅ Best
KNN Regressor	0.80

## Preferred Model: Linear Regression (high accuracy, simplicity, and interpretability)

## 📈 Final Results
R² Score: 91%

Features Used: 6 (after dropping x, y, z)

Preprocessing & Modeling: Done from scratch using Python

### Conclusion: Linear Regression model delivers strong and consistent performance

### Contact
If you have any questions, suggestions, or would like to collaborate, feel free to reach out:

👤 Name: Aditya Barahate 📧 Email: adityabarhate18@gmail.com
