# 📊 Telco Customer Churn Prediction

## Project Overview

Churn is among the major problems that confront subscription-oriented companies. Customer retention tends to be less costly compared to customer acquisition. Churn prediction can thus be considered a critical problem within the business world.

In this project, we design a machine learning model aimed at predicting the probability of churn of a telecommunications customer through various factors such as demographics of the customer, subscriptions, contracts, and billing. The entire process of data science will be covered, including data preprocessing and exploratory data analysis (EDA).


## Business Problem

The main objective of this project is to identify customers who are likely to discontinue their services so that the company can implement targeted customer retention strategies.


## Dataset

**Dataset:** IBM Telco Customer Churn Dataset

The dataset contains information on over 7,000 customers, including:

* Customer demographics
* Services subscribed
* Account information
* Billing information
* Customer churn status

Target Variable:

* **Churn**

  * 0 = Customer stayed
  * 1 = Customer churned

## Machine Learning Models

The following classification models were developed and evaluated:

* Logistic Regression
* Random Forest Classifier

---

## Model Performance

| Model               |   Accuracy |    ROC-AUC |
| ------------------- | ---------: | ---------: |
| Logistic Regression | **80.38%** | **0.8366** |
| Random Forest       |     79.39% |     0.8215 |

### Logistic Regression Performance

| Metric    |  Score |
| --------- | -----: |
| Accuracy  | 80.38% |
| Precision |    65% |
| Recall    |    57% |
| F1-score  |    61% |
| ROC-AUC   | 0.8366 |

### Random Forest Performance

| Metric    |  Score |
| --------- | -----: |
| Accuracy  | 79.39% |
| Precision |    64% |
| Recall    |    51% |
| F1-score  |    57% |
| ROC-AUC   | 0.8215 |

---

## Model Selection

The reason behind the selection of the Logistic Regression model was its superior performance in predicting the target class.

When compared to the Random Forest model, it performed better in terms of:

* Higher Accuracy
* Higher ROC-AUC
* Higher Precision
* Higher Recall
* Higher F1-score

Moreover, the logistic regression model gives interpretable coefficients that allow understanding which factors influence the customer churn.

## Key Business Insights

Some of the key determinants that emerged from the exploratory data analysis include the following:

* Customers with month-to-month plans had higher levels of churn compared to those with long-term plans.
* Fiber internet plan customers had higher churn.
* Shorter tenure was a predictor of churn.
* More charges per month predicted higher churn.
* Senior citizens had a higher rate of churn compared to non-senior customers.


## Business Recommendations

From the research findings, the telecommunication company can be advised to:

* Provide incentives for switching customers from their monthly contracts to long-term contracts.
* Initiate retention strategies for at-risk customers.
* Keep track of customers paying high monthly rates.
* Provide adequate customer service to high-risk customers.
* Use predictive analytics to identify at-risk customers.

## Future Improvements

Future work could include:

* Hyperparameter optimization
* Cross-validation
* Feature selection
* Application of other machine learning models like XGBoost, LightGBM, CatBoost, and SVM
* Deployment of the model using Flask, FastAPI, or Streamlit framework
* Development of Power BI dashboard

## Author

**Damian Brian Mwakodi**

BSc Statistics | Data Science & Machine Learning Enthusiast

I am passionate about applying statistics and machine learning to solve real-world business problems through data-driven decision-making.
