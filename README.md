
# Predictive Maintenance for Wind Turbines using Machine Learning

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

## Project Overview

Wind turbines operate in harsh environmental conditions and are prone to unexpected mechanical failures. 
Unplanned downtime leads to significant operational losses and increased maintenance costs.

This project develops a machine learning-based predictive maintenance system that analyzes turbine sensor data 
to identify early signs of generator failure. By predicting failures in advance, operators can schedule 
preventive maintenance and avoid costly breakdowns.

The project demonstrates how data science can be applied to renewable energy systems to improve reliability and efficiency.

---

## Business Problem

Wind turbine failures can result in:

- Expensive repair costs
- Loss of electricity generation
- Operational downtime
- Reduced equipment lifespan

Traditional maintenance strategies include:

| Strategy | Description |
|--------|-------------|
| Reactive Maintenance | Repair after failure occurs |
| Preventive Maintenance | Scheduled maintenance regardless of condition |
| Predictive Maintenance | Maintenance based on predicted failures |

This project focuses on predictive maintenance using machine learning.

---

## Dataset

Source: Kaggle – Renewind Wind Turbine Dataset

The dataset contains sensor measurements from wind turbine generators.

### Dataset Dimensions

| Dataset | Rows | Columns |
|------|------|------|
| Training Data | 20,000 | 41 |
| Testing Data | 5,000 | 41 |

### Features

- 40 sensor variables
- 1 target variable

Target variable:

0 → Normal turbine  
1 → Generator failure

### Class Distribution

Training Dataset:

| Class | Count |
|------|------|
| No Failure | 18,890 |
| Failure | 1,110 |

Testing Dataset:

| Class | Count |
|------|------|
| No Failure | 4,718 |
| Failure | 282 |

This indicates a class imbalance problem which is common in predictive maintenance datasets.

---

## Machine Learning Pipeline

Data Collection  
↓  
Exploratory Data Analysis  
↓  
Data Preprocessing  
↓  
Handling Class Imbalance  
↓  
Feature Preparation  
↓  
Model Training  
↓  
Model Evaluation  
↓  
Performance Comparison  

---

## Models Implemented

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

Models are compared using classification metrics to determine the best model for predicting turbine failures.

---

## Model Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

### Confusion Matrix Interpretation

| Outcome | Meaning |
|------|------|
| True Positive | Failure correctly predicted |
| True Negative | Normal turbine correctly predicted |
| False Positive | False alarm |
| False Negative | Failure not detected |

In predictive maintenance, False Negatives are the most costly because a failure occurs without warning.

---

## Project Structure

mlba/

predictive-maintenance-for-wind-turbines-using-ml.ipynb  
Train.csv  
Test.csv  
README.md  

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Installation

Clone the repository:

git clone https://github.com/bbhatia9/mlba.git  
cd mlba

Install required libraries:

pip install pandas numpy scikit-learn matplotlib seaborn jupyter

Run Jupyter Notebook:

jupyter notebook

Open:

predictive-maintenance-for-wind-turbines-using-ml.ipynb

---

## Applications

Predictive maintenance systems like this can be applied in:

- Wind turbine monitoring
- Manufacturing equipment
- Industrial machinery
- Aircraft engine diagnostics
- Power plant operations
- Smart grid infrastructure

---

## Key Benefits

- Reduced equipment downtime
- Lower maintenance costs
- Improved operational efficiency
- Increased asset lifespan
- Early failure detection

