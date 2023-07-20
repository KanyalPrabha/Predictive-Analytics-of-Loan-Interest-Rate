Project Description - Loan Interest Rate Predictive Analytics:

Summary: 
---------
This project involves analyzing loan data from Lending Club, where loans were granted to individuals. The dataset contains various features related to borrowers and the loan amounts they were given.

Objective: 
-----------
The main goal is to examine the factors that have the most significant impact on the interest rates offered by Lending Club. Additionally, the analysis focuses on understanding the sociodemographic aspects of borrowers and their preferred loan types.

Data Preparation:
-----------------
Performed feature selection and cleaned the data by handling noisy entries (e.g., removing symbols like '%', 'k' for thousands).
Addressed missing data through imputation using mode and median values.
Converted qualitative variables into dummy variables for analysis.
Checked and managed data skewness using Yeho Johnson transformation.
Addressed multicollinearity by removing correlated features (correlation > 0.8).
Conducted Principal Component Analysis (PCA) for dimension reduction, although the extracted components were not ultimately utilized.

Methods Used:
-------------
Utilized the following predictive models:

Multiple Linear Regression (MLR)
Multivariate Adaptive Regression Splines (MARS)
Regularized regression techniques
Decision trees and Random Forest (using bagging)

Evaluation Metric:
------------------
The model performance was assessed using the test Root Mean Squared Error (RMSE).

This project aims to gain insights into the factors influencing loan interest rates, and various machine learning techniques were employed to develop predictive models and evaluate their performance based on the RMSE metric.
