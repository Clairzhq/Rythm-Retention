# Rythm-Retention

## Project Overview

This project uses logistic regression to predict which customers are likely to cancel their subscription, based on the past three months of subscription and listening history data.

## Process Summary

* Cleaned and prepared customer and listening history data
* Engineered features such as number of sessions, percent of Pop and Podcast consumption, and cancellation status
* Performed exploratory data analysis to uncover patterns in user behavior
* Built and evaluated a logistic regression model

## Key Findings

* Customers with fewer sessions are more likely to cancel
* A higher percentage of Pop music consumption is associated with higher cancellation rates
* Discounts and podcast listening do not significantly affect cancellation behavior

## Model Performance

* Accuracy: approximately 77.78%
* Features used: Number of sessions, Pop music percentage
* Evaluation metrics: Confusion matrix and classification report

## Business Insights

* Encouraging more frequent listening may help reduce churn
* Discount offers may not be an effective retention strategy
* Further analysis may be needed to understand why Pop-heavy users are canceling

## Tools and Technologies

* Python (Pandas, NumPy, Scikit-learn)
* Jupyter Notebook
* Excel

---
