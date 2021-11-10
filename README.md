# Project Overview
A data science project to predict customers who churn "leave" the company by analyzing all relevant customer data and developing focused customer retention programs 

# The Data:
The data is sourced from Kaggle (https://www.kaggle.com/blastchar/telco-customer-churn). Our dataset contains 7043 entries representing 7043 unique customers. There are 21 columns, with 19 features (target feature = 'Churn'). The features are numeric and categorical in nature, so we will need to address these differences before modeling.

# Results:
The final results comparing several models are shown below:
| Model | Recall | Percision | Specificity | F1 |
| ------ | ------ | ------ | ------ | ------ |
| AdaBoost (default) | 0.5081| 0.6283 | 0.8943 | 0.5619 |
| AdaBoost (tuned for better recall) |0.8934 | 0.4880 | 0.6705 | 0.6312 |
| Logistic regression (default) | 0.5382 | 0.6234 | 0.8856 | 0.5777 |
| Logistic regression (tuned for better recall) | 0.8524 | 0.5008 | 0.7012 | 0.6309 |
| Random Forest (default) | 0.4672 | 0.6576 | 0.9145 | 0.5463 |
| Random Forest (tuned for better recall) | 0.8278 | 0.5224 | 0.7339 | 0.6405 |
| SVC (default) | 0.5109 | 0.6296 | 0.8943 | 0.5641 |
| SVC  (tuned for better recall) | 0.7923 | 0.4841 | 0.7031 | 0.6010 |

