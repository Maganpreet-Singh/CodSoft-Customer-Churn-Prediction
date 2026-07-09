# Customer Churn Prediction

## About the Project

Customer churn prediction is a critical business problem that helps organizations identify customers who are likely to discontinue using their services. By predicting churn in advance, companies can take proactive measures to improve customer retention and reduce revenue loss.

This project develops and compares multiple machine learning models to predict customer churn using customer demographic and account-related information. Since the dataset contains an imbalanced target variable, SMOTE (Synthetic Minority Oversampling Technique) is used to balance the training data and improve the model's ability to identify churned customers.

---

## Objectives

* Analyze customer data and identify factors related to churn.
* Handle class imbalance using SMOTE.
* Build and compare multiple machine learning classification models.
* Evaluate model performance using industry-standard metrics.
* Predict whether a customer is likely to churn or remain with the company.

---

## Dataset Features

The dataset includes customer information such as:

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Account Balance
* Number of Products
* Credit Card Ownership
* Active Membership Status
* Estimated Salary

### Target Variable

**Exited**

* 0 → Customer Stayed
* 1 → Customer Churned

---

## Data Preprocessing

The following preprocessing techniques were applied:

* Removal of irrelevant columns
* One-Hot Encoding of categorical variables
* Feature Scaling using StandardScaler
* Stratified Train-Test Split
* SMOTE Oversampling for class balancing

---

## Machine Learning Models

### Logistic Regression

A baseline linear classification algorithm used for binary classification tasks.

### Random Forest Classifier

An ensemble learning technique that combines multiple decision trees to improve predictive accuracy and reduce overfitting.

### Gradient Boosting Classifier

A boosting algorithm that sequentially improves model performance by correcting the errors of previous learners.

---

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix

Special emphasis was placed on Recall and ROC-AUC due to the imbalanced nature of customer churn datasets.

---

## Results

The ensemble learning models demonstrated superior performance compared to the baseline Logistic Regression model.

* Random Forest achieved strong predictive accuracy.
* Gradient Boosting delivered the best overall classification performance.
* SMOTE significantly improved the identification of churned customers.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Imbalanced-Learn (SMOTE)
* Jupyter Notebook

---

## Future Enhancements

* Hyperparameter Optimization
* XGBoost and LightGBM Implementation
* Feature Importance Analysis
* Model Deployment with Flask or Streamlit
* Real-Time Churn Prediction Dashboard

---

## Author

**Maganpreet Singh**

Computer Science Undergraduate | Machine Learning Enthusiast
