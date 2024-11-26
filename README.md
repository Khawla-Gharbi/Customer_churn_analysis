# Customer Churn Prediction Using Machine Learning

This project involves building a machine learning model to predict customer churn for a retail business using the Telco Customer Churn dataset.  
The workflow includes data preprocessing, exploratory data analysis (EDA), and feature engineering.  
A Random Forest Classifier was implemented, achieving an accuracy of ~85%.  
The project highlights feature importance and provides actionable insights for customer retention strategies.

## Features:
- **CustomerID**: Unique identifier for each customer.  
- **Gender**: Whether the customer is male or female.  
- **SeniorCitizen**: Indicates if the customer is a senior citizen (1) or not (0).  
- **Partner**: Whether the customer has a partner (Yes/No).  
- **Dependents**: Whether the customer has dependents (Yes/No).  
- **Tenure**: Number of months the customer has been with the company.  
- **PhoneService**: Whether the customer has phone service (Yes/No).  
- **MultipleLines**: Whether the customer has multiple phone lines (Yes/No/No phone service).  
- **InternetService**: Type of internet service (DSL, Fiber optic, None).  
- **OnlineSecurity**: Whether the customer has online security add-ons (Yes/No).  
- **OnlineBackup**: Whether the customer has online backup add-ons (Yes/No).  
- **DeviceProtection**: Whether the customer has device protection add-ons (Yes/No).  
- **TechSupport**: Whether the customer has tech support add-ons (Yes/No).  
- **StreamingTV**: Whether the customer has streaming TV services (Yes/No).  
- **StreamingMovies**: Whether the customer has streaming movie services (Yes/No).  
- **Contract**: The type of customer contract (Month-to-month, One year, Two year).  
- **PaperlessBilling**: Whether the customer has opted for paperless billing (Yes/No).  
- **PaymentMethod**: The payment method (Electronic check, Mailed check, Bank transfer, Credit card).  
- **MonthlyCharges**: The customer’s monthly bill amount.  
- **TotalCharges**: Total amount charged to the customer.  
- **Churn**: The target variable indicating whether the customer churned (Yes/No).  

## Tools & Technologies:
- **Python**: pandas, scikit-learn, matplotlib, seaborn
- **Machine Learning Model**: Random Forest Classifier
- **Jupyter Notebook**: For data analysis and modeling
