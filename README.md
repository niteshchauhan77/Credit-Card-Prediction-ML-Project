# Credit-Card-Prediction-ML-Project
Utilize machine learning approaches to predict credit card approval based on customer information.
A bank's credit card department is one of the top adopters of data science. A top focus for the bank has always been acquiring new credit card customers. Giving out credit cards without doing proper research or evaluating applicants' creditworthiness is quite risky. The credit card department has been using a data-driven system for credit assessment called Credit Scoring for many years, and the model is known as an application scorecard. A credit card application's cutoff value is determined using the application scorecard, which also aids in estimating the applicant's level of risk. This decision is made based on strategic priority at a given time.

# Objectives 
The objective of this project is to build a machine learning model that predicts whether the customers are eligible for approval of credit card or not and the model takes into account various factors related to authorization of credit card approval applications. The target of this machine learning model is to upgrade the credit card approval process and make it fast, reliable, secure and time efficient. Besides this the machine learning model also removes extra manpower required by banks for finding the reliable candidates from all the applicants and helps bank in decreasing the workload. 

# Datasets
  1. Credit_card.csv
     Ind_ID: Client ID
     Gender: Gender information
     Car_owner: Having car or not
     Propert_owner: Having property or not
     Children: Count of children
     Annual_income: Annual income
     Type_Income: Income type
     Education: Education level
     Marital_status: Marital_status
     Housing_type: Living style
     Birthday_count: Use backward count from current day (0), -1 means yesterday.
     Employed_days: Start date of employment. Use backward count from current day (0). Positive value means, individual is currently unemployed.
     Mobile_phone: Any mobile phone
     Work_phone: Any work phone
     Phone: Any phone number
     EMAIL_ID: Any email ID
     Type_Occupation: Occupation
     Family_Members: Family size

  2. Credit_card_label.csv
     ID: The joining key between application data and credit status data, same is Ind_ID
     Label: 0 is the application approved and 1 is the application rejected.

# Steps Implemented in the Machine Learning Project
1. Merging both the Dataframes together.
2. Data Exploration and Understanding the data.
3. Checking for Null values,Expressing them as percentages and visualising them on Heatmap
4. Imputation of null values
5. Data Visualisation of Multiple Category columns using Pie Plot and Bar Plot
6. Histogram for Univariate Analysis of Numerical Columns
7. Checking Outliers using Box Plot
8. Seprating the dataframe in Numerical and Categorical Columns
9. Grouping each Individual Independent feature with Dependent Feature
10. Saving the cleaned dataset
11. Encoding the Categorical Features in Dataframe
12. Checking the Independent Features for Multicollinearity
13. Splitting the Dataframe in Independent Features and Depedendent Feature
14. Feature Importance
15. Recursive Feature Elimination
16. Train-Test Split
17. Feature Scaling
18. Defining a Function for calculation of Metrics
19. Training Machine Learning Models on Imbalanced Dataset(Using 8 models)
20. SMOTE
21. Train Test Split After SMOTE
22. Feature Scaling After SMOTE
23. Training Machine Learning Models on Balanced Dataset(Using 8 models)
24. Predictions on Test Data
25. SQL QUERIES
