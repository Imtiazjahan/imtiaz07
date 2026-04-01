# 🏦 Bank Term Deposit Prediction using Logistic Regression

## 📌 Introduction

This project focuses on predicting whether a customer will subscribe to
a term deposit based on their banking behaviour.

A Logistic Regression model is used to classify customers into two
categories: - Yes (Subscribed) - No (Not Subscribed)

------------------------------------------------------------------------

## 📂 Dataset

The dataset used is the Bank Marketing Dataset.

It contains information about customers such as: - Age - Job - Marital
status - Education - Account details - Previous marketing interactions

Target variable: - y → Whether the customer subscribed (yes/no)

------------------------------------------------------------------------

## ⚙️ Approach

### 1. Data Preprocessing

-   Checked for missing values
-   Converted categorical data into numeric using Label Encoding
-   Separated features (X) and target (y)

------------------------------------------------------------------------

### 2. Model Building

-   Used Logistic Regression from sklearn
-   This model is suitable for binary classification problems

------------------------------------------------------------------------

### 3. Training

-   Split data into training and testing sets (80% / 20%)
-   Trained the model using training data

------------------------------------------------------------------------

## 📊 Results

-   The model was evaluated using:
    -   Accuracy score
    -   Confusion Matrix
    -   Classification Report
-   The model performs well in predicting customer responses.

------------------------------------------------------------------------

## 📈 Observations

-   Logistic Regression works effectively for this type of problem
-   Proper encoding of categorical variables is important
-   Model performance depends on data quality

------------------------------------------------------------------------

## 🚀 Future Improvements

-   Use feature scaling for better performance
-   Try advanced models like Decision Tree or Random Forest
-   Perform hyperparameter tuning
-   Handle class imbalance if present

------------------------------------------------------------------------

## 🛠️ Tools Used

-   Python\
-   Pandas\
-   Scikit-learn\
-   Matplotlib / Seaborn\
-   Google Colab

------------------------------------------------------------------------

## ✅ Conclusion

The Logistic Regression model successfully predicts whether a customer
will subscribe to a term deposit. This helps banks improve their
marketing strategies and target the right customers.

------------------------------------------------------------------------
