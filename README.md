# Customer-Churn-Project
Telecom Customer Churn Analysis

In the dynamic landscape of the telecom industry, retaining customers is paramount. This project meticulously analyzes company data to unveil the reasons behind customer churn and devises proactive measures to prevent it.

Key Models and Findings:

Linear Regression (Tenure vs. Monthly Charges)
Performance: Root Mean Squared Error: 29.08

Logistic Regression (Monthly Charges vs. Churn)
Performance:
Confusion Matrix:
[[1797 0]
[ 669 0]]
Accuracy Score: 0.73

Multiple Logistic Regression (Tenure, Monthly Charges vs. Churn)
Performance:
Confusion Matrix:
[[944 92]
[193 180]]
Accuracy Score: 0.80

Decision Tree Classifier (Tenure vs. Churn)
Performance:
Confusion Matrix:
[[951 85]
[257 116]]
Accuracy Score: 0.76

Random Forest Classifier (Tenure, Monthly Charges vs. Churn)
Performance:
Confusion Matrix:
[[1327 212]
[ 311 263]]
Accuracy Score: 0.75

Insights and Recommendations:
The Multiple Logistic Regression model stands out with an impressive 0.80 accuracy score, indicating its efficacy in predicting customer churn. To enhance customer retention, consider refining marketing strategies, especially for the two-year plan. Innovative offers on contract phones could be a game-changer in reducing churn rates.
