# customer_churn-analysis

This project aims to analyze customer churn using data analytics techniques. It involves data cleaning, preprocessing, exploratory data analysis (EDA), and predictive modeling to identify factors influencing customer retention.

Dataset Description:

 The dataset contains the following fields:
 
 ● CustomerID: Unique identifier for each customer.
 
 ● Gender: Male or Female.
 
 ● SeniorCitizen: Whether the customer is a senior citizen (1) or not (0).
 
 ● Partner: Whether the customer has a partner (Yes or No).
 
 ● Dependents: Whether the customer has dependents (Yes or No).
 
 ● Tenure: Number of months the customer has stayed with the company.
 
 ● PhoneService: Whether the customer has phone service (Yes or No).
 
 ● MultipleLines: Whether the customer has multiple lines (Yes, No, No phone service).
 
 ● InternetService: Customer’s internet service provider (DSL, Fiber optic, No).
 
 ● OnlineSecurity: Whether the customer has online security service (Yes, No, No
 internet service).
 
 ● OnlineBackup: Whether the customer has online backup (Yes, No, No internet
 service).
 
 ● DeviceProtection: Whether the customer has device protection (Yes, No, No internet
 service).
 
 ● TechSupport: Whether the customer has tech support (Yes, No, No internet service).
 
 ● StreamingTV: Whether the customer streams TV (Yes, No, No internet service).
 
 
 ● StreamingMovies: Whether the customer streams movies (Yes, No, No internet
 service).
 
 ● Contract: Type of customer contract (Month-to-month, One year, Two year).
 
 ● PaperlessBilling: Whether the customer uses paperless billing (Yes or No).
 
 ● PaymentMethod: Customer’s payment method (Electronic check, Mailed check, Bank
 transfer, Credit card).
 
 ● MonthlyCharges: The amount charged to the customer monthly.
 
 ● TotalCharges: The total amount charged to the customer.
 
 ● Churn:Whether the customer has churned (Yes or No).

 Project Workflow

# Data Cleaning & Preprocessing

Handling missing values

Encoding categorical variables

Scaling numerical features

Removing outliers

# Exploratory Data Analysis (EDA)

Visualizing churn patterns

Correlation analysis

Identifying key churn factors

# Insights & Features

Key Features Influencing Churn:

Customers with shorter tenure are more likely to churn.

Higher monthly charges correlate with increased churn risk.

Contract type plays a significant role, with month-to-month contracts having the highest churn rates.

Customers with multiple services tend to have lower churn rates.

# Behavioral Insights:

Customers who engage more frequently with support services tend to have higher retention rates.

Discounts and loyalty programs can help in reducing churn rates.
