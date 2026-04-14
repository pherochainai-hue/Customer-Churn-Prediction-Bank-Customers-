Objective

The goal of this project is to predict customer churn in a bank using machine learning techniques. Churn refers to customers who are likely to leave the bank. By identifying such customers early, the bank can take proactive steps to improve retention.

Dataset

We used the Churn Modelling Dataset, which contains customer information such as:

Credit Score
Geography
Gender
Age
Tenure
Balance
Number of Products
Has Credit Card
Is Active Member
Estimated Salary
Churn (Target Variable)

Approach

1. Data Cleaning & Preparation
Removed irrelevant columns such as RowNumber, CustomerId, and Surname.
Checked for missing values (none found).
Verified data types and ensured consistency.

2. Encoding Categorical Variables
Gender → Label Encoding (Male = 1, Female = 0)
Geography → One-Hot Encoding (France, Germany, Spain)

3. Feature Scaling
Applied standardization (e.g., StandardScaler) to normalize numerical features.

4. Model Training
Split dataset into training and testing sets (typically 80/20).
Trained classification models such as:
Logistic Regression
Random Forest Classifier
(Optional) XGBoost / Decision Tree

5. Model Evaluation
Evaluated performance using:
Accuracy
Confusion Matrix
Precision, Recall, F1-score

Results & Insights

 Key Findings from Feature Importance
Age → Older customers are more likely to churn.
Balance → Customers with higher balances tend to leave more often.
Geography (Germany) → Higher churn rate compared to other regions.
IsActiveMember → Inactive customers are much more likely to churn.
Number of Products → Customers with fewer products are more likely to leave.

 Model Performance
Random Forest performed best with strong accuracy and generalization.
Logistic Regression provided good interpretability but slightly lower performance.

 Skills Demonstrated
Data preprocessing and cleaning
Categorical feature encoding (Label Encoding, One-Hot Encoding)
Supervised machine learning (classification)
Model evaluation and comparison
Feature importance analysis and business insights

 Conclusion

This project demonstrates how machine learning can help banks identify customers at risk of churn. By leveraging insights from the model, businesses can design targeted strategies such as personalized offers, improved engagement, and better customer service to reduce churn and increase retention.
