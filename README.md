# Credit_Card_Fraud_Prediction

# Overview
Credit card fraud prediction involves using machine learning and data analysis techniques to identify patterns and anomalies in credit card transactions that may indicate fraudulent activity. By analyzing various features such as transaction amount, location, time, and frequency, predictive models can be trained to detect suspicious transactions in real-time or batch processing. These models help financial institutions and businesses mitigate risks, minimize losses, and enhance security measures by flagging potentially fraudulent transactions for further investigation or action.

# Problem
The Problem is to predict whether the transcation is fraud or not via credit card

# Dataset
Trans_date_trans_time: Timestamp of the transaction (date and time).
Cc_num:Unique customer identification number.
MerchantThe merchant involved in the transaction.
Category Transaction type (e.g., personal, childcare).
Amt:Transaction amount.
First: Cardholder's first name.
Last Cardholder's last name.
Gender: Cardholder's gender.
Street: Cardholder's street address.
City: Cardholder's city of residence.
State: Cardholder's state of residence.
Zip: Cardholder's zip code.
Lat:Latitude of cardholder's location.
Long: Longitude of cardholder's location.
City_pop:Population of the cardholder's city.
Job:Cardholder's job title.
Dob: Cardholder's date of birth.
Trans_num: Unique transaction identifier.
Unix_time: Transaction timestamp (Unix format).
Merch_lat:Merchant's location (latitude).
Merch_long: Merchant's location (longitude).
Is_fraud:Fraudulent transaction indicator (1 = fraud, 0 = legitimate). This is the target variable for classification purposes.

# Libraries
- Pandas: To Process the data as the data was in CSV format.
- Matplotlib and Seaborn : It is commonly used for data visualization and creating various types of charts and plots.
- Scikit-learn: Scikit-Learn, also known as Sklearn is a python library to implement machine learning models and statistical modelling.

# EDA Pre-Processing
To perform EDA is one of the most important thing to do before applying any Machine Learning Model .It make sures that data is been validate and no outliers are present
Eda and pre procession steps -
- handling the missing value
- converting categorial to numeric
- feature scaling(Standard scaling)
- Handling outliers (value more than IQR is outliers)
- Train test split


# Machine Learning Model
Based on Independent Variables the problem is Multi Classification the best 3 Algorithm will be (i.e)
- Logistic Regression
- Random Forest
- ADA Boost

# Logistic Regression
![image](https://github.com/SakaataGintoki/Credit_Card_Fraud_Prediction/assets/107795560/5a07ff34-3de0-4ae1-8acc-d156c05d23a3)
![image](https://github.com/SakaataGintoki/Credit_Card_Fraud_Prediction/assets/107795560/56cbde0d-2da0-4a61-8e16-416a336e078c)

# Evaluation
![image](https://github.com/SakaataGintoki/Credit_Card_Fraud_Prediction/assets/107795560/0fd1234e-61bd-490e-b67d-79030a614dca)

# Random Forest Algorithm
![image](https://github.com/SakaataGintoki/Credit_Card_Fraud_Prediction/assets/107795560/821120e1-0f5f-4662-aab4-a5d61dde7580)
![image](https://github.com/SakaataGintoki/Credit_Card_Fraud_Prediction/assets/107795560/c58a3cb9-69df-40b3-b500-54cacb81a33d)

# Evaluation
![image](https://github.com/SakaataGintoki/Credit_Card_Fraud_Prediction/assets/107795560/11ca40d8-c545-4fc7-bc43-4ad7e3bccec0)

# ADA Boost Algorithm
![image](https://github.com/SakaataGintoki/Credit_Card_Fraud_Prediction/assets/107795560/9fa73040-f1b8-4d47-8f18-e63a456d821d)

# Evaluation
![image](https://github.com/SakaataGintoki/Credit_Card_Fraud_Prediction/assets/107795560/5c9f1f1c-29d4-479e-b355-f7677e79267b)

# Results and Comparision
![image](https://github.com/SakaataGintoki/Credit_Card_Fraud_Prediction/assets/107795560/5af4bcdf-7745-482e-9588-1e7a8a0ab32d)





