# Credit Risk Machine Learning Model Performance Analysis

Summary:
This analysis was done to evaluate the performance of a logistic regression model trained to predict loan risk. The model is intended to classify loans into two categories: healthy loans (class 0) and high-risk loans (class 1). This analysis assesses the accuracy, precision, and recall of the model to determine its effectiveness in making predictions.

Results:
Accuracy Score: 0.99
Healthy Loan Precision: 1
Healthy Loan Recall: 0.99
High Risk Loan Precision: 0.85
High Risk Recall: 0.91

Analysis:
A logistic regression model works well for identifying binary results of healthy or high risk loans because it not only classifies the data linearly, but it also predicts the probability that a result belongs to a certain class. This regression model demonstrates extremely high performance for healthy loans, with a perfect precision score of 1 and a recall score of 0.99. This indicates that the model rarely misclassifies healthy loans and capture the majority of them very well. The high accuracy score of 0.99 indicates strong predictive capability. The precision score for high risk loans is slightly lower at 0.85, but the model maintains a respectable recall score at 0.91. There are some false positives, but the model is effective at identifying the majority of actual high risk loans, which helps the firm identify and prevent actual risk. 
I recommend deploying this logistic regression model. It has the ability to accurately classify loans into healthy and high risk categories to aid in decision making on risk assessment. 
