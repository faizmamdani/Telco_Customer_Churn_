# Telco_Customer_Churn_
**Problem Statement**:-Predicting Customer Churn in a Telecom Company


![image](https://github.com/faizmamdani/Telco_Customer_Churn_/assets/135321547/454d0233-934e-4cd6-81ab-7899c7eabba3)

![image](https://github.com/faizmamdani/Telco_Customer_Churn_/assets/135321547/89d999fa-d941-49a2-a924-2067d9b92dcf)




**Model applying **:-logistic Regression and Support vector machine(SVM)

**Overall Conclusion for Logistic regression** :-The logistic regression model demonstrates reasonable predictive performance in identifying customer churn. It achieved an accuracy of approximately 80.64%, indicating that it can make correct predictions for a large portion of the test dataset. However, there is room for improvement, especially in correctly identifying churned customers (class 1.0). The model's precision, recall, and F1-score for class 1.0 (churn) are relatively lower compared to class 0.0 (non-churn). Depending on the business's priorities and objectives, further model tuning, feature engineering, or trying different algorithms may be considered to enhance the predictive performance and reduce churn more effectively. It is essential to consider the business context and potential costs associated with false positives and false negatives when interpreting the model's performance and deciding on next steps. Continuous monitoring and feedback can help fine-tune the model and implement effective retention strategies.

**Overall Conclusion for SVM **: The SVM model's performance for predicting customer churn is highly imbalanced and inadequate. While it shows perfect accuracy in predicting non-churn cases (class 0.0), it completely fails to identify churned customers (class 1.0). The model's precision, recall, and F1-score for class 1.0 are all extremely low, indicating that it does not provide any meaningful predictions for churn. The model's inability to detect churn (class 1.0) renders it unsuitable for practical use in predicting customer churn. The lack of any true positive predictions for churn shows that the model could not learn meaningful patterns to distinguish churn from non-churn customers.
