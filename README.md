# Telecom Customer Churn Analysis - Leo Telecom

### Project Overview:
You are a Data Scientist at Leo Telecom, tasked with addressing the issue of customer churn. Leo Telecom has observed a significant number of customers leaving for competitors. The goal of this project is to analyze the provided customer data, uncover key insights, and develop strategies to prevent churn, ensuring improved customer retention.

### Problem Statement:
The telecom industry is highly competitive, and customer churn is a major challenge. This project focuses on understanding why customers are leaving Leo Telecom and aims to build a data-driven solution to identify customers at risk of churn. Using customer data, we will:

Analyze the factors contributing to churn:
Develop a predictive model to classify which customers are likely to leave.
Provide actionable insights for the business to reduce churn and improve customer retention.

### Dataset Information:
The dataset contains various customer attributes that help analyze their behavior. Some of the key attributes include:

CustomerID: Unique identifier for each customer.
Tenure: Duration (in months) the customer has stayed with the company.
Contract Type: Type of contract (monthly, yearly, etc.).
Internet Service: Type of internet service (DSL, Fiber optic, None).
Monthly Charges: Monthly fee paid by the customer.
Total Charges: Total amount charged over the entire tenure.
Payment Method: Mode of payment (Credit card, Bank transfer, etc.).
Churn: Whether the customer has churned (Yes/No).


### Project Structure
Data Preprocessing: Handling missing values, outliers, and transforming data where necessary.
Exploratory Data Analysis (EDA): Understanding the dataset, identifying key trends, and discovering factors that contribute to customer churn.
Feature Engineering: Creating new features that might improve the predictive model's performance.
Model Development: Building machine learning models to predict churn, focusing on accuracy, precision, recall, and AUC.
Here 3 models are built using combinations of features for input:
#### 1. using ‘tenure’ as the feature and ‘Churn’ as the dependent/target column
#### 2. using ‘tenure’ as the feature and ‘Churn’ as the dependent/target column with a dropout layer each after input and hidden layers.
#### 3. using ‘Tenure’, ’Monthly Charges’ & ‘Total Charges’ as the features and ‘Churn’ as the dependent/target column

### Model Evaluation: Evaluating the model on performance metrics and tuning it for better results.
Insights & Recommendations: Providing actionable insights based on model predictions and analysis to reduce churn.

### Tools & Technologies
Python: Primary programming language for analysis and modeling.
Pandas & NumPy: For data manipulation and analysis.
Matplotlib & Seaborn: For data visualization.
Scikit-learn: For building machine learning models.
Jupyter Notebooks: For interactive coding and analysis.
