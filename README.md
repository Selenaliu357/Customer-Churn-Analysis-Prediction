# Customer Churn Analysis Prediction

Customer churn occurs when a customer stops using a company’s service lead to revenue loss. Analyzing churn helps businesses understand why customers leave and how to improve retention. High churn rates can affect revenue and business growth. By analyzing churn patterns businesses can take proactive steps to retain customers.

In this project we will explore the Telco Customer Churn dataset to predict churn effectively.

- tenure – The number of months a customer has stayed with the company.
- InternetService – The type of internet service the customer has DSL, Fiber optic or None.
- PaymentMethod– The method the customer uses for payments.
- Churn – The target variable i.e Yes for customer churned and No for customer stayed

## Steps:
#### Step 1: Importing Libraries and Dataset
#### Step 2: Data Preprocessing
- Handling Missing and Incorrect Values
- Handling Categorical Variables
- Feature Selection and Splitting Data
- Feature Scaling
#### Step3: Model Training and Prediction
- Training the model we use Random Forest Classifier
#### Step 4: Model Evaluation
- Accuracy Score: to measure model performance we calculate accuracy using the accuracy_score function
- Confusion Matrix and Performance Metrics: we evaluate precision, recall and accuracy using a confusion matrix

## End
Confusion matrix shows how well the model predicts customer churn. It correctly identifies 924 non-churners and 181 churners. However 117 non-churners are wrongly classified as churners and 187 churners are missed. The high number of missed churners suggests the model may need further tuning.
