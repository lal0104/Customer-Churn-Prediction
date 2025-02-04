## Customer Churn Prediction

## 📌 Problem Definition
The Dataset contains `Customer Churn table` which contains information of `7,043` customers from a `Telecommunications company` that provide home phone and Internet services in California in Q3.<br>

The data set includes information about:<br>

Customers who left within the last month – the column is called Churn<br>
Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies<br>
Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges<br>
Demographic info about customers – gender, age range, and if they have partners and dependents

<br>

## 📓 Exploratory Data Analysis

Inferences:

1. HIGH Churn seen in case of Month to month contracts, No online security, No Tech support, First year of subscription and Fibre Optics Internet
2. LOW Churn is seens in case of Long term contracts, Subscriptions without internet service and The customers engaged for 5+ years
3. Factors like Gender, Availability of PhoneService and multiple lines have alomost NO impact on Churn

Some Visualizations:<br>
<img src = "/assets/Screenshot 2025-02-05 001350.png">
<img src = "/assets/Screenshot 2025-02-05 001621.png">
<img src = "/assets/Screenshot 2025-02-05 001523.png">
<img src = "/assets/Screenshot 2025-02-05 001548.png">


## 📓 Overview

| Machine Learning Models Applied            | Accuracy |
| ----------------- | ------------------------------------------------------------------ |
| Random Forest | 81.10% |
| Logistic Regression | 80.61% |
| Support Vector Machine | 81.73% |
| XGB_Classifier | 80.52% |
| Gradient Boasting | 82.37% |

<img src = "/assets/Screenshot 2025-02-05 001119.png">

The Dataset was imbalanced so to increase the accuracy I applied SMOTE and then the accuracy of gradient boasting classifier reached `95.12%`.

<img src = "/assets/Screenshot 2025-02-05 001021.png">

<br>

## 👉 Application

The ability to predict churn before it happens allows businesses to take proactive actions to keep existing customers from churning. This could look like: 
```
  Customer success teams reaching out to those high-risk customers to provide support or to gauge 
  what needs may not be being met.
```

The advantage of calculating a company's churn rate is that it provides clarity on how well the business is retaining customers, which is a reflection on the quality of the service the business is providing, as well as its usefulness.

<br>


## 🔗 Dataset:

<a href='https://www.kaggle.com/datasets/blastchar/telco-customer-churn' target="_blank"><img alt='Kaggle' src='https://img.shields.io/badge/Kaggle-100000?style=for-the-badge&logo=Kaggle&logoColor=20beff&labelColor=black&color=FFFFFF'/></a>

<br >

## 👉 Conclusion

Conducted in-depth statistical analysis using EDA to identify churn drivers from a dataset of 7,043 customers, focusing on key business metrics like tenure and monthly charges.<br>
Engineered a Gradient Boosting model, achieving 95% accuracy in predicting customer churn and generating actionable insights that improved customer retention.

 
