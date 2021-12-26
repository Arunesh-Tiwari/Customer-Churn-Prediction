# Customer-Churn-Prediction
Churn prediction is a common use case in machine learning domain. If you are not familiar with the term, churn means “leaving the company”. It is very critical for a business to have an idea about why and when customers are likely to churn. Having a robust and accurate churn prediction model helps businesses to take actions to prevent customers from leaving the company.
I used “Telco Customer Churn” dataset which is available on Kaggle.
There are 20 independent variables and 1 dependent variable for 7043 customers. Target variable indicates if a customer has left the company (i.e. churn=yes) within the last month. Since the target variable has two states (yes/no or 1/0), this is a binary classification problem.
The variables are: 'customerID', 'gender', 'SeniorCitizen', 'Partner', 'Dependents', 'tenure', 'PhoneService', 'MultipleLines', 'InternetService', 'OnlineSecurity', 'OnlineBackup', 'DeviceProtection', 'TechSupport', 'StreamingTV', 'StreamingMovies', 'Contract', 'PaperlessBilling', 'PaymentMethod', 'MonthlyCharges', 'TotalCharges', 'Churn'.
At first glance, only customerID seems irrelevant to customer churn. Other variables may or may not have an effect on customer churn. We will figure out.

<h3>The project follows:</h3>
Exploratory Data Analysis<br>
Data Preprocessing<br>
Model Creation and Evaluation<br>
Improving the Model<br>
