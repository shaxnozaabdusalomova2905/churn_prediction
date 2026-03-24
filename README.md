# churn_prediction
ML  project to predict customer churn using logistic regression
# Customer Churn Prediction

## Project Overview

This project aims to predict customer churn using a machine learning model. The goal is to identify customers who are likely to leave, allowing businesses to take preventive actions.

## Dataset

The dataset used is the Telco Customer Churn dataset, which includes customer demographics, account information, and service usage.

## Steps Performed

* Data cleaning and preprocessing
* Handling categorical variables using one-hot encoding
* Feature scaling using StandardScaler
* Model training using Logistic Regression
* Model evaluation using accuracy, precision, recall, and ROC-AUC
* Threshold tuning to improve recall

##  Results

* Accuracy: ~78%
* Recall: ~62%
* Precision: ~57%
* F1 score: ~60% 

The model shows a trade-off between precision and recall. Improving recall helps detect more churners, which is important for business decision-making.

##  Key Insights

* The model misses some churners (false negatives), which impacts recall
* Adjusting the classification threshold improves churn detection
* Class imbalance affects model performance

##  Future Improvements

* Try advanced models (Random Forest, XGBoost)
* Perform hyperparameter tuning
* Improve feature engineering
* Handle class imbalance more effectively

##  Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib / Seaborn

##  How to Run

1. Clone the repository
2. Open the notebook
3. Run all cells
