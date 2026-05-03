# Marketing & Product Performance Analysis

## Overview
This project focuses on analyzing marketing and product performance data to understand what drives customer revenue. The main goal is to build machine learning models that can predict whether a customer generates high or low revenue.

---

## Dataset
I used the **Marketing and Product Performance Dataset** available on Kaggle:

https://www.kaggle.com/datasets/imranalishahh/marketing-and-product-performance-dataset

The dataset contains various features such as budget, clicks, conversions, ROI, and customer-related attributes.

---

## Objective
The objective of this project is:
- To predict customer revenue level (high or low)
- To compare different machine learning models
- To identify important features affecting performance

---

## Research Questions
1. How well does a basic model perform?
2. Which model gives better results?
3. Does scaling improve performance?
4. Which features are most important?
5. Can tuning improve the model?
6. How well does the model classify results?
7. What final insights can we draw?

---

## Methodology
The following steps were followed:
- Data cleaning and preprocessing
- Converting categorical variables
- Creating a binary target variable
- Splitting data into training and testing sets
- Training models (Logistic Regression, Random Forest)
- Feature scaling
- Hyperparameter tuning
- Model evaluation

---

## Results Summary
- Random Forest performed better than Logistic Regression
- Feature scaling slightly improved performance
- Hyperparameter tuning improved accuracy further
- Important features include:
  - Bundle Price
  - Budget
  - ROI
  - Clicks

---

## Project Files
The project is divided into multiple notebooks:
- RQ1: Baseline Model
- RQ2: Model Comparison
- RQ3: Feature Scaling
- RQ4: Feature Importance
- RQ5: Model Tuning
- RQ6: Model Evaluation
- RQ7: Final Conclusion

---

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Conclusion
The project shows that machine learning can help identify key factors affecting revenue. Random Forest with tuning provided the best results and can be useful for business decision-making.

---

## Author
Dharmik Bhisara
