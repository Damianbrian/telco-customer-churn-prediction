# 📊 Telco Customer Churn Prediction

## Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. Retaining existing customers is generally more cost-effective than acquiring new ones, making churn prediction an important business problem.

This project develops a machine learning model to predict whether a telecommunications customer is likely to churn based on customer demographics, service subscriptions, contract details, and billing information. The project follows the complete data science workflow, from data preprocessing and exploratory data analysis (EDA) to model development, evaluation, and business recommendations.

---

## Business Problem

The objective is to identify customers who are likely to discontinue their services so that the company can implement targeted customer retention strategies.

---

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

---

## Project Workflow

1. Data loading
2. Data cleaning
3. Exploratory Data Analysis (EDA)
4. Feature engineering
5. Categorical variable encoding
6. Train-test split
7. Model development
8. Model evaluation
9. Model comparison
10. Business recommendations

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

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

Logistic Regression was selected as the final model because it achieved the highest overall predictive performance.

Compared with Random Forest, it produced:

* Higher Accuracy
* Higher ROC-AUC
* Higher Precision
* Higher Recall
* Higher F1-score

In addition, Logistic Regression provides interpretable coefficients that help explain which factors contribute most to customer churn, making it useful for business decision-making.

---

## Key Business Insights

The exploratory data analysis identified several important factors associated with customer churn:

* Customers on month-to-month contracts were significantly more likely to churn than those on longer-term contracts.
* Customers with fiber optic internet services exhibited higher churn rates.
* Customers with shorter tenure were more likely to leave.
* Higher monthly charges were associated with increased churn.
* Senior citizens showed a higher likelihood of churning than non-senior customers.

---

## Business Recommendations

Based on the findings, the telecommunications company should consider:

* Offering incentives for customers to migrate from month-to-month contracts to long-term contracts.
* Developing targeted retention campaigns for high-risk customers.
* Monitoring customers with high monthly charges.
* Improving customer support for customers identified as high churn risks.
* Using predictive analytics to proactively identify customers requiring retention interventions.

---

## Future Improvements

Future work may include:

* Hyperparameter tuning
* Cross-validation
* Feature selection
* Testing additional machine learning algorithms such as XGBoost, LightGBM, CatBoost, and Support Vector Machines
* Model deployment using Flask, FastAPI, or Streamlit
* Building an interactive Power BI dashboard

---

## Author

**Damian Brian Mwakodi**

BSc Statistics | Data Science & Machine Learning Enthusiast

I am passionate about applying statistics and machine learning to solve real-world business problems through data-driven decision-making.
