# E-commerce Sales Analysis & Machine Learning

## Project Overview
This project analyzes an e-commerce dataset (200+ records) to uncover customer purchasing patterns, sales trends, and build a machine learning model to predict sales.

---

## Objectives
- Perform data cleaning and preprocessing
- Analyze sales trends and customer behavior
- Visualize key insights using charts
- Build a machine learning model for prediction

---

## Dataset Information
- Total Records: 200+
- Features:
  - Order_ID
  - Date
  - Customer_ID
  - Product
  - Category
  - Price
  - Quantity
  - City

- Includes missing values (NaN) to simulate real-world data

---

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Data Preprocessing
- Converted date column to datetime format
- Handled missing values using mean/mode imputation
- Created new feature: **Total_Sales = Price × Quantity**

---

## Exploratory Data Analysis (EDA)
- Sales by category
- Top-selling products
- City-wise sales distribution
- Sales trends over time

---

## Machine Learning Model
- Model Used: Linear Regression
- Features: Price, Quantity
- Target: Total_Sales

---

## Model Evaluation
- R² Score: 0.57 (approx)
- Mean Absolute Error (MAE): ~18,000
- Mean Squared Error (MSE): High due to squared values

---

## Key Insights
- Electronics category generated the highest revenue
- Laptops and phones are top-selling products
- Metro cities contributed the most sales
- Strong relationship between price, quantity, and total sales

---

## Conclusion
The analysis and model demonstrate how data can be used to understand sales patterns and make predictions. This can help businesses improve decision-making and revenue strategies.

---
