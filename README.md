# Credit-Risk-Classification

# Table of Content
- credit_risk_classification.ipynb
- Resources - lending_data.csv

# References of code sourced from
- Monash Lesson Plans - Supervised Learning

# Credit Risk Analysis Report
An overview of the analysis: Explain the purpose of the analysis
-To assess the performance of a logistic regression model in predicting whether a loan applicant is creditworthy. To evaluate the ability of the model to classify whether a loan applicant is a healthy loan or a high risk loan. If the model can accurately identify high risk loan applicants that will help decide whether to approve or deny applications.

The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.
-Accuracy score: The overall accuracy of the model is 99%, which means that it correctly predicts 99% of all instances in the testing data. -Precision score: For 0 (healthy loan), precision is 1.00, which means that when the model predicts a loan as "healthy", it is correct 100% of the time. For 1 (high-risk loan), precision is 0.85, which means that when the model predicts a loan as "high-risk", it is correct 85% of the time. -Recall score: For 0 (healthy loan), recall is 0.99, which means that the model correctly identifies 99% of the actual healthy loans. For 1 (high-risk loan), recall is 0.91, which means that the model captures 91% of the actual high-risk loans.

A summary: Summarise the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning. 
-The machine learning model has high precision and recall score for both classes (0 and 1), demonstrating its ability to effectively classify loan applicants as healthy or high-risk. The strong precision and recall score on the dataset is a good indication about how well the model is likely to perform in real life. This is important for credit risk assessment. -The f1-score for both classes are well-balanced, which indicates that the model does not favor one class at the expense of the other. -The overall accuracy of the model is 99%, which means that it correctly predicts 99% of all instances in the testing data. -The model is supported by a substantial number of instances for both healthy and high-risk loans. -The strong performance of the model in predicting high-risk loans is critical in minimising financial losses and managing credit risk. -Based on the strong performance of the logistic regression model, I would recommend the model for use by the company. The ability of the model to accurately classify loans as healthy or high-risk, the balanced f1-scores, and high overall accuracy make it a valuable tool for decision support in loan approvals.
