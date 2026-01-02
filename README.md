# Customer_Purchase_Behavior_Analysis---Machine-Learning
End-to-end ML project analyzing Amazon customer purchase behavior. Includes data preprocessing, K-Means customer segmentation, CLV prediction using Linear Regression, churn prediction using Logistic Regression, and an interactive Power BI dashboard to support retention, revenue forecasting, and targeted marketing.

Objectives
Segment customers based on spending, purchase frequency, and loyalty
Predict Customer Lifetime Value (CLV) for revenue forecasting
Identify customers at risk of churn
Translate analytical results into actionable business insights

Dataset
The dataset contains customer demographics, purchase history, loyalty indicators, discount usage, payment methods, and churn information.
A cleaned and ML-ready version of the dataset is included in this repository.

Tools & Technologies
Python: pandas, numpy, scikit-learn
Jupyter Notebook
Power BI Desktop
Machine Learning Models:
K-Means Clustering
Linear Regression
Logistic Regression

Project Workflow
Task 1: Customer Segmentation (K-Means Clustering)
Customer-level aggregation
Features used: total spend, purchase frequency, loyalty score
Feature scaling and Elbow Method to select optimal clusters
Customers segmented into Low Value, Occasional, and High Value (VIP)
Business Impact: Enables targeted promotions and personalized engagement.

Task 2: Customer Lifetime Value Prediction (Linear Regression)
Target: Customer Lifetime Value
Features: age, purchase amount, loyalty score, discount usage, payment method
One-hot encoding and missing value imputation
Model evaluated using R², MAE, and RMSE
Coefficients analyzed to identify key CLV drivers
Business Impact: Supports predictive marketing and efficient resource allocation.

Task 3: Customer Churn Prediction (Logistic Regression)
Target: Churn (0 = Active, 1 = Churned)
Behavioral and demographic predictors used
Model evaluated using classification metrics
Key churn drivers identified (loyalty, discounts, payment methods)
Business Impact: Helps design proactive retention strategies.

Power BI Dashboard
An interactive multi-page Power BI dashboard was created using the cleaned dataset, including:
Executive Overview (KPIs and high-level trends)
Customer Segmentation insights
CLV & Revenue analysis
Churn analysis with slicers for interactivity
