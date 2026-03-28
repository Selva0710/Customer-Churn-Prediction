Customer Churn Prediction using Machine Learning

 Project Overview

This project focuses on predicting customer churn using machine learning techniques. Customer churn refers to customers who stop using a company’s services. Identifying such customers helps businesses take proactive measures to retain them.

Objectives

* Load and preprocess the dataset
* Handle missing and irrelevant data
* Convert categorical variables into numerical format
* Train machine learning models for churn prediction
* Compare model performance
* Implement rule-based churn logic
* Visualize results using graphs

 Dataset Description

The dataset used is a telecom customer dataset containing demographic, service, and billing-related information.

 Selected Features

* Age – Customer age
* Monthly Charges / Total Charges – Used as a proxy for Income/Purchases
* Contract Type – Used as Membership category
* Customer Status – Used to derive Churn (target variable)

 Data Preprocessing

* Removed unnecessary columns (CustomerID, Zip Code, Latitude, Longitude, etc.)
* Converted "Total Charges" to numeric format
* Handled missing values by removing null records
* Encoded categorical variables using Label Encoding
* Converted target variable into binary (Churn: 0 = No, 1 = Yes)

 Machine Learning Models Used

 1. Logistic Regression

* A baseline classification algorithm
* Assumes a linear relationship between features and target
* Easy to interpret

 2. Random Forest Classifier ⭐

* An ensemble learning algorithm
* Handles non-linear relationships effectively
* Reduces overfitting using multiple decision trees
* Provides higher accuracy compared to baseline models

 Model Performance

| Model               | Accuracy  |
| ------------------- | --------- |
| Logistic Regression | 76.3%     |
| Random Forest       | 81.7%     |

 Observations

* Random Forest achieved higher accuracy
* Improved precision and recall for churn prediction
* Better at capturing complex patterns in the data

Visualizations

The following visualizations were generated:

* Confusion Matrix
* Feature Importance Graph
* Correlation Heatmap
* ROC Curve
* Model Comparison Bar Graph

 Rule-Based Logic

A simple rule-based system was implemented:

* Customers with short tenure and basic contract are likely to churn
* Customers with high charges and low usage duration are at higher risk

This logic simulates real-world business rules.

 Conclusion

The Random Forest model performed best with an accuracy of 81.7%, outperforming Logistic Regression.
It is the most suitable model for this task as it captures complex relationships and improves prediction performance.

 Future Improvements

* Apply SMOTE to handle class imbalance
* Perform hyperparameter tuning
* Use advanced models such as XGBoost
* Deploy the model using Flask or Streamlit

 Deliverables

* Jupyter Notebook (`.ipynb`)
* Dataset (`.csv`)
* README file

 Author

Name: Selva Nidharshana.S
Course: Artificial Intelligence and Machine Learning


