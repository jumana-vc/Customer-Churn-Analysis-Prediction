# Customer Churn Analysis and Prediction Using Python

## Project Overview
This project focuses on analysing and predicting customer churn in the telecommunications industry using Python.

The main objective is to understand customer behaviour, identify patterns associated with customer churn, build machine learning models to predict customer churn, and provide business recommendations that may help improve customer retention.

## Business Problem
Customer churn is a major challenge for telecommunications companies. Losing customers can affect revenue and long-term business growth.

This project analyses customer data to identify factors associated with customer churn and uses machine learning algorithms to predict whether a customer is likely to leave the service.

## Project Objectives
- Understand overall customer churn.
- Analyse customer complaints and churn patterns.
- Examine customer behaviour and service usage.
- Study churn patterns across age groups and tariff plans.
- Explore relationships between numerical variables.
- Build machine learning models for churn prediction.
- Compare model performance and identify the best-performing model.
- Provide business insights and recommendations.

## Dataset
**Dataset:** Iranian Telecom Customer Churn Dataset

**Source:** UCI Machine Learning Repository

https://archive.ics.uci.edu/dataset/563/iranian+churn+dataset

- Original records: 3,150
- Records after duplicate removal: 2,850
- Missing values: None

## Tools and Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## Project Workflow
1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Customer Churn Analysis
5. Data Visualization
6. Correlation Analysis
7. Data Preprocessing
8. Train-Test Split
9. Machine Learning Model Building
10. Model Evaluation and Comparison
11. Feature Importance Analysis
12. Customer Churn Prediction
13. Business Insights and Recommendations

## Key Findings
- The overall customer churn rate was approximately 15.65%.
- Customers who reported complaints had a considerably higher churn rate.
- Churned customers showed lower average call usage and SMS frequency.
- Customers aged 45 had the highest churn rate among the age groups analysed.
- Tariff Plan 1 showed a higher churn rate than Tariff Plan 2.
- Customer Value was positively correlated with Frequency of SMS.

## Machine Learning Models
Six machine learning algorithms were implemented and evaluated:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Naive Bayes

## Model Performance

| Model | Accuracy |
|---|---:|
| Logistic Regression | 90.35% |
| KNN | 94.74% |
| Decision Tree | 91.23% |
| Random Forest | 96.14% |
| SVM | 93.33% |
| Naive Bayes | 71.05% |

**Best Model: Random Forest**

Random Forest achieved the highest accuracy of 96.14%.

It also achieved:
- Precision: 94%
- Recall: 81%
- F1-Score: 87%

Based on the overall evaluation, Random Forest was selected as the best-performing model.

## Business Insights
- Customer complaints are strongly associated with churn.
- Lower service usage is observed among churned customers.
- Customer engagement may play an important role in customer retention.
- Different tariff plans show different churn patterns.

## Business Recommendations
- Improve complaint handling and customer support.
- Monitor customers with declining service usage.
- Review tariff plans to understand differences in customer retention.
- Develop customer engagement and retention strategies.
- Monitor customer satisfaction regularly.
- Use churn prediction models to help identify customers who may be at risk of leaving.

## Project Limitations
This project uses a historical dataset for exploratory analysis and machine learning.

The findings show associations and patterns in the dataset and do not establish direct causation. Model performance on this dataset may differ when applied to new real-world customer data.

## Project Files
- Jupyter Notebook (`.ipynb`)
- Project Report (`.pdf`)
- Dataset (`.csv`)
- Saved Random Forest Model (`.pkl`)

## Conclusion
This project demonstrates how Python-based data analysis and machine learning can help identify customer churn patterns, predict potential customer churn, and generate useful business insights for the telecommunications industry.

---

**Project by: Jumana**