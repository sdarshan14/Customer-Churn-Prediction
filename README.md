# Customer Churn Prediction

## Overview

This project focuses on analyzing customer behavior and predicting customer churn using machine learning techniques. Customer churn refers to customers discontinuing a service or leaving a company. The goal of this project is to identify patterns that contribute to customer attrition and build a predictive model that helps businesses improve customer retention.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset

Dataset: Telco Customer Churn Dataset

The dataset contains customer information including:

- Demographics
- Account Information
- Service Usage
- Contract Type
- Monthly Charges
- Total Charges
- Churn Status

## Project Structure

```text
Customer_Churn_Prediction/
│
├── charts/
│   ├── churn_distribution.png
│   ├── gender_vs_churn.png
│   ├── tenure_analysis.png
│   ├── monthly_charges.png
│   ├── correlation_heatmap.png
│   ├── confusion_matrix.png
│   └── feature_importance.png
│
├── output/
│   └── cleaned_customer_churn.csv
│
├── customer_churn_prediction.ipynb
├── customer_churn_prediction.py
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
└── README.md
```

## Objectives

- Analyze customer churn behavior.
- Identify factors influencing churn.
- Perform exploratory data analysis.
- Visualize important customer trends.
- Build a machine learning model for churn prediction.
- Evaluate model performance.

## Features

### Exploratory Data Analysis

- Churn Distribution Analysis
- Gender vs Churn Analysis
- Customer Tenure Analysis
- Monthly Charges Analysis
- Correlation Analysis

### Machine Learning

- Data Preprocessing
- Label Encoding
- Train-Test Split
- Random Forest Classification
- Model Evaluation

### Model Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report
- Feature Importance Analysis

## How to Run

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run the Project

```bash
python customer_churn_prediction.py
```

## Generated Outputs

### Visualizations

- churn_distribution.png
- gender_vs_churn.png
- tenure_analysis.png
- monthly_charges.png
- correlation_heatmap.png
- confusion_matrix.png
- feature_importance.png

### Processed Dataset

- cleaned_customer_churn.csv

## Key Insights

- Analyze customer attrition patterns.
- Identify high-risk customer groups.
- Understand the relationship between tenure and churn.
- Evaluate the impact of monthly charges on churn.
- Determine the most important factors affecting customer retention.

## Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Data Encoding
6. Model Training
7. Model Evaluation
8. Feature Importance Analysis

## Future Enhancements

- Hyperparameter Tuning
- Multiple Model Comparison
- Customer Segmentation
- Churn Probability Dashboard
- Real-Time Prediction System
- Streamlit Web Application
- Power BI Dashboard Integration

## Expected Business Impact

- Improve customer retention strategies.
- Reduce customer acquisition costs.
- Identify customers likely to churn.
- Enable data-driven business decisions.
- Increase long-term customer value.

## Author

Bhashyam Sree Darshan
