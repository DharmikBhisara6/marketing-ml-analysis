# Marketing & Product Performance Analysis

## Dataset
I used the **Marketing and Product Performance Dataset** available on Kaggle:

https://www.kaggle.com/datasets/imranalishahh/marketing-and-product-performance-dataset

The dataset contains various features such as budget, clicks, conversions, ROI, and customer-related attributes.

---

## Objective
The objective of this project is:

- To predict customer revenue level (high or low) using machine learning models  
- To compare different machine learning models  
- To identify important features affecting performance  

---

## Research Questions
1. How well does a basic model perform?  
2. Which model gives better results?  
3. Does scaling improve performance?  
4. Which features are most important?  
5. Does hyperparameter tuning improve model performance?  
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
- A subset of the dataset was used to improve computational efficiency  

---

## Results Summary
- Random Forest achieved higher accuracy compared to Logistic Regression  
- Feature scaling improved the performance of Logistic Regression  
- Key features influencing revenue include Budget, ROI, and Bundle Price  
- Hyperparameter tuning significantly improved model performance  
- The model demonstrates reasonable generalization based on cross-validation  

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
This project demonstrates the practical application of machine learning techniques in solving real-world marketing analytics problems.

---

## Author
Dharmik Bhisara

---

## Note
All experiments were conducted using Kaggle notebooks with full execution outputs.
