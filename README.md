# Telecom-Churn-Case-Study
Telecom Churn Case Study - Kaggle

# 0. Problem statement

In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

For many incumbent operators, retaining high profitable customers is the number one business
goal. To reduce customer churn, telecom companies need to predict which customers are at high risk of churn. In this project, you will analyze customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn, and identify the main indicators of churn.

In this competition, your goal is *to build a machine learning model that is able to predict churning customers based on the features provided for their usage.*

**Customer behaviour during churn:**

Customers usually do not decide to switch to another competitor instantly, but rather over a
period of time (this is especially applicable to high-value customers). In churn prediction, we
assume that there are three phases of customer lifecycle :

1. <u>The ‘good’ phase:</u> In this phase, the customer is happy with the service and behaves as usual.

2. <u>The ‘action’ phase:</u> The customer experience starts to sore in this phase, for e.g. he/she gets a compelling offer from a competitor, faces unjust charges, becomes unhappy with service quality etc. In this phase, the customer usually shows different behaviour than the ‘good’ months. It is crucial to identify high-churn-risk customers in this phase, since some corrective actions can be taken at this point (such as matching the competitor’s offer/improving the service quality etc.)

3. <u>The ‘churn’ phase:</u> In this phase, the customer is said to have churned. In this case, since you are working over a four-month window, the first two months are the ‘good’ phase, the third month is the ‘action’ phase, while the fourth month (September) is the ‘churn’ phase.

## Link to the dataset
https://www.kaggle.com/competitions/telecom-churn-case-study-hackathon-c-66

The repo contains a jupyter notebook (Telecom churn case study.ipynb file)

## Table of Contents 
1. Problem Statement
2. Data Cleaning and Missing Data imputation with KNN Imputer
3. EDA
   1. Univariate
   2. Bivariate
4. Train Test Split
5. Feature Selection
       1.RFE
       2.PCA
6. Feature Engineering
    1. Scaling
    2. Class Imbalance Handling with Adaptive Synthetic Sampling
7. Model Creation
    1. Logistic Regression
    2. SVC
    3. Decision Tree
    4. Random Forest (Bagging)
    5. AdaBoostClassifier (Boosting)
    6. GradientBoostingClassifier (Boosting)
    7. XGBClassifier (Boosting)
8. HyperParameter Tuning
9. Working with unseen data
10. Feature Importance & Business Recommendations 
