# Customer-Churn-Prediction - IE0005 Mini Project
This repository contains the source code and resources for the mini-project on **Machine Learning for Customer Churn Prediction**, completed as part of the **IE0005: Intro to Data Science & AI** module at Nanyang Technological University (NTU).

## Project-Overview
Customer churn refers to the phenomenon where customers stop using a company's product or service. Predicting churn allows businesses to take proactive measures to retain valuable customers. In this project, we apply machine learning techniques to predict whether a customer will churn based on their profile and service usage.

## Machine Learning Approach
We explored and compared several models:

- Logistic Regression  
- Random Forest  
- XGBoost  
- Support Vector Machine (SVM)
- CatBoost
- (and more...)

**Evaluation Metrics:**

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- ROC-AUC Score

## TL;DR
This project successfully predicted customer churn using several machine learning models. The **Random Forest** model achieved the highest overall accuracy of **~76.0%**, closely followed by **CatBoost (Optimized)** with **~76.11%**, and **LightGBM** with **~75.40%**.

While **Random Forest** and **LightGBM** provided balanced performance, **XGBoost** and **CatBoost (with high `scale_pos_weight`)** stood out for their strong ability to identify churned customers, with **recall scores above 0.72**, making them especially valuable for minimizing customer loss.

## Future Work
To further improve prediction accuracy and model generalization, future work could explore:
- Deep learning models (e.g., neural networks)
- Real-time churn prediction systems for dynamic customer retention strategies
