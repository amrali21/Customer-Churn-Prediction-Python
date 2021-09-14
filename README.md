# Project Overview
***
A data science project to predict customers who churn "leave" the company by analyzing all relevant customer data and developing focused customer retention programs 

# The Data:
***
The data is sourced from Kaggle (https://www.kaggle.com/blastchar/telco-customer-churn). Our dataset contains 7043 entries representing 7043 unique customers. There are 21 columns, with 19 features (target feature = 'Churn'). The features are numeric and categorical in nature, so we will need to address these differences before modeling.

# Results:
***
The final results comparing several models are shown below:
| Model | Recall | Percision | Specificity | F1 |
| ------ | ------ | ------ | ------ | ------ |
| Logistic regression (default) | 0.5738 | 0.7079 | 0.9185 | 0.6338 |
| Logistic regression (tuned for better recall) | 0.8133 | 0.5122 | 0.7334 | 0.6286 |
| Random Forest (default) | 0.5041 | 0.7448 | 0.9405 | 0.6013 |
| Logistic regression (tuned for better recall) | 0.6908 | 0.6375 | 0.8648 | 0.6631 |
| AdaBoost (default) | 0.5543| 0.7289 | 0.9290 | 0.6297 |
| AdaBoost (tuned for better recall) |0.8272 | 0.5147 | 0.7315 | 0.6346 |