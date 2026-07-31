# Period-Symptom-and-Date-Prediction
Built something different for Girlfriend’s Day.  Periods can be unpredictable — cramps, fatigue, bloating, mood swings, and changing cycle patterns. So I thought, why not use data to make things a little more predictable?  I built a Menstrual Cycle &amp; Symptom Prediction Dashboard that:  Predicts upcoming period length Predicts the upcoming symptom 

# Menstrual Cycle & Symptom Prediction Dashboard

A Machine Learning and Power BI project designed to analyze menstrual cycle patterns, predict period length and upcoming symptoms, and provide general self-care suggestions.

## Project Overview

Menstrual cycles can vary from person to person and across different cycles. This project explores how historical cycle and lifestyle data can be used with Machine Learning to identify patterns and generate predictions.

The final predictions are integrated into an interactive Power BI dashboard for easy visualization.

## Key Features

- Predicts upcoming **Period Length**
- Predicts **Upcoming Symptoms**
- Provides symptom-based **Self-Care Suggestions**
- Tracks previous period and cycle history
- Analyzes symptom frequency
- User-specific Power BI dashboard
- Interactive filtering using User ID and Period Count

## Machine Learning Approach

Two separate ML pipelines were developed:

### 1. Period Length Prediction
**Problem Type:** Regression

Models tested:
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

### 2. Upcoming Symptom Prediction
**Problem Type:** Multiclass Classification

Models tested:
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

The preprocessing workflow was built using:

- `Pipeline`
- `ColumnTransformer`
- `OneHotEncoder`
- `StandardScaler`
- `SimpleImputer`

## Feature Engineering

Historical features were created to capture previous cycle behaviour:

- Previous Period Length
- Previous Cycle Length
- Previous Symptom
- Average Cycle Length
- Average Period Length
- Period Count

These features allow each cycle to use information from previous recorded cycles.

## Dashboard

The Power BI dashboard includes:

- Upcoming Symptom
- Previous Symptom
- Previous Cycle Information
- Period Length Trend
- Symptom Distribution
- Suggested Self-Care
- User-specific filtering

## Tech Stack

- Python
- Pandas
- Scikit-learn
- Machine Learning
- Power BI
- DAX
- Excel / CSV

## Project Workflow

Dataset  
→ Data Cleaning  
→ Feature Engineering  
→ Preprocessing  
→ Regression & Classification  
→ Model Evaluation  
→ Prediction Generation  
→ Power BI Dashboard

## Disclaimer

This project is developed for educational and data analytics purposes only.

The predictions and self-care suggestions are not intended to provide medical diagnosis, treatment, or professional medical advice.

## Author

**Amey Samarth**

Data Analytics | Machine Learning | Power BI
