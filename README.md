## Predicting Heart Disease with Machine Learning
This project investigates the use of machine learning techniques to predict heart disease, a leading cause of death globally. By analyzing patient data and key risk factors, we aim to support early detection and improve health outcomes.

# Overview
Dataset: Heart Disease dataset from Kaggle (Cleveland, Hungary, Switzerland, Long Beach V)
Observations: 303 patient records
Attributes: 14 features including age, cholesterol, chest pain type, blood pressure, and more
Target Variable: Presence or absence of heart disease

# Methodology
We applied a multidisciplinary approach combining:
Data Preprocessing: Cleaning and formatting in Excel and CSV
Database Design: SQL Server with ERD via Lucidchart
ETL Pipeline: Built using SSIS in Visual Studio
Statistical Analysis: Descriptive stats, correlation, and distribution insights

# Machine Learning Models:
Logistic Regression (Accuracy: 82.2%)
Decision Tree (J48, Accuracy: 78.5%)
Instance-Based Learning (K=9, Accuracy: 82.5%)
OneR (Accuracy: 72.3%)
Cost Sensitivity Analysis: Prioritized minimizing false negatives to reduce misdiagnosis risk

# Key Findings
Top Predictors: Cholesterol, maximum heart rate, chest pain type
Correlations: Strong links between chest pain and heart rate with disease presence
Visualization Tools: Tableau for treemaps, scatter plots, and time series trends
Business Intelligence: Weka for model evaluation and cost-sensitive learning

# Automation and Analytics
Business Process Automation: Python scripts to flag at-risk patients based on thresholds
Web Analytics: Google Alerts and infographics to promote heart health awareness
Prescriptive Strategies:
Lifestyle changes
Community fitness programs
Wearable tech for real-time monitoring

# Limitations
Dataset size: 303 samples
Data age: From 1988, may not reflect current trends
Need for larger, more diverse datasets for future research

# References
CDC Heart Attack Info
Mayo Clinic Cardiovascular Research
Kaggle Dataset
