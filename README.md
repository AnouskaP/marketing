# Customer Analytics & Sales Prediction

## Project Overview
This project focuses on customer analytics, sales prediction, and segmentation using **data science and machine learning techniques**. The goal is to analyze customer behavior, predict future sales, and improve marketing strategies through data-driven insights.

## Dataset
- The dataset includes customer transactions, discount usage, marketing spend, and tax information.
- Key features include **Transaction Date, Product Category, Sales Amount, Customer ID, Discount Percentage**, and more.

## Project Workflow
### 1. **Data Preprocessing**
   - Load and clean multiple datasets.
   - Convert date formats and merge datasets.
   - Handle missing values and outliers.
   
### 2. **Exploratory Data Analysis (EDA)**
   - Identify trends in customer acquisition and retention.
   - Analyze the impact of discounts on revenue.
   - Perform time-series analysis to understand seasonality.
   
### 3. **Customer Segmentation (RFM & Clustering)**
   - Use **Recency, Frequency, and Monetary (RFM) segmentation** to categorize customers.
   - Apply **K-Means clustering** for customer grouping.
   
### 4. **Sales Prediction**
   - Feature selection using **F-Regression & VIF (Variance Inflation Factor)**.
   - Train models using **Decision Trees, XGBoost, and GridSearchCV**.
   - Evaluate performance using **classification reports and ROC-AUC scores**.
   
### 5. **Cross-Selling Analysis**
   - Implement **Market Basket Analysis** using **Apriori Algorithm**.
   - Generate **association rules** for product recommendations.
   
### 6. **Predicting Next Purchase Day**
   - Train models to estimate when a customer is likely to make their next purchase.
   - Handle class imbalance using **SMOTE (Synthetic Minority Over-sampling Technique)**.
   
### 7. **Cohort Analysis**
   - Track customer retention over time using **heatmaps**.
   - Analyze revenue and order patterns across different cohorts.

## Installation & Dependencies
To run this project, install the required Python libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost imbalanced-learn mlxtend
```

## Usage
Clone the repository and run the Jupyter Notebook:

```bash
git clone https://github.com/anouskap/marketing.git
cd Marketing-Insights-for-E-Commerce
jupyter notebook

## Results & Findings
- Identified key factors influencing customer retention and revenue.
- **Decision Trees achieved 77% accuracy**, while **XGBoost reached 82%** in predicting customer lifetime value.
- Implemented **market basket analysis** to enhance cross-selling strategies.

## Future Work
- Experiment with **deep learning models** for better sales forecasting.
- Improve segmentation using **hierarchical clustering**.
- Incorporate **real-time recommendation systems** for personalized marketing.
