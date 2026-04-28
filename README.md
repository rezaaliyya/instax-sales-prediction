# 📊 Sales Prediction using Instax Transaction Data

## 📌 Overview
This project analyzes Instax sales transaction data to uncover business insights and build predictive models for estimating total sales. The analysis covers EDA, feature engineering, and machine learning to support data-driven decision making.

## 🎯 Objectives
- Understand sales patterns based on product, time, location, and customer behavior
- Identify key factors influencing total sales
- Build and compare machine learning models for prediction
- Provide actionable business insights

## 📂 Dataset
Instax sales transaction dataset, including:
- Transaction date
- Product name & category
- Unit price & quantity
- Discount
- Total sales
- Payment method
- Store location

## 🔎 Key Insights
- Sales show consistent seasonality patterns
- A few top products contribute most of the revenue
- Payment methods are relatively balanced
- Store location impacts sales performance
- Unit price has the strongest correlation with total sales

## ⚙️ Data Processing
- Handled missing values and ensured data consistency
- Converted date features and extracted month, day, week
- Applied encoding (Label Encoding & One-Hot Encoding)
- Performed feature engineering (holiday flag, discount flag)
- Applied StandardScaler and split data (80:20)

## 🤖 Models
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

## 📊 Evaluation
- MAE, RMSE, R² Score
- Best model: XGBoost Regressor (highest overall performance)

## 📈 Business Recommendations
- Focus on high-performing products and categories
- Optimize promotions based on seasonal trends
- Maintain all payment methods for flexibility
- Use model for sales forecasting

## 🛠️ Tools
Python (Pandas, NumPy, Matplotlib, Seaborn), Scikit-learn, XGBoost, Power BI

## 📊 Dashboard
Interactive dashboard built using Power BI  
(Add screenshot here)

## 📄 Report
Full report includes data understanding, EDA, preprocessing, modeling, and business recommendations
