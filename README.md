# Challenge_20_Supervised_ML

## Background
In this challenge, you’ll use various techniques to train and evaluate a model based on loan risk. The objective is to leverage a dataset of historical lending activity from a peer-to-peer lending services company and build a model capable of identifying the creditworthiness of borrowers.


# Credit Risk Analysis Report

## Credit Risk Classification Overview:
This analysis aims to utilize machine learning to forecast credit risk in peer-to-peer lending. The lending dataset incorporates information such as loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, total debt, and loan status. The primary objective is to predict whether a loan is low-risk (healthy) or high-risk.

**Dataset Composition:**
The dataset comprises 75,036 healthy loans and 2,500 high-risk loans. To conduct the analysis, the dataset underwent a division into training and testing sets.

**Model Training Process:**
  - Split the Data into Training and Testing Sets
  - Create a Logistic Regression Model with the Original Data

## Results 
**Machine Learning Model's Results:**
  
  **- Accuracy:** 99%
  
  **- Precision:**
              
              + Healthy Loans: 1.00
              
              + High-Risk Loans: 0.87
              
  **- Recall:**
  
              + Healthy Loans: 1.00
              
              + High-Risk Loans: 0.89

## Summary 
The machine learning models, particularly the logistic regression model, exhibit notable results. The model attains flawless accuracy in predicting healthy loans (0 label), achieving both 100% precision and recall. However, when it comes to predicting high-risk loans (1 label), precision stands at 87%, and recall at 89%, indicating a substantial margin of error in this specific category. Despite this, the overall accuracy score for the model is commendable at 99%, suggesting a generally effective model with room for improvement, particularly in identifying high-risk loans.

If the primary concern is correctly identifying healthy loans (0 label), the current model of Logistic Regression appears to perform exceptionally well with perfect precision and recall. On the other hand, if the focus is on high-risk loans (1 label), the model's challenges in precision and recall indicate a potential area for improvement.

The choice of model performance may hinge on the importance of accurate predictions in the specific problem scenario. For instance, if the consequences of misclassifying high-risk loans are more critical, there may be a need to explore additional models or techniques, such as resampling method, to enhance performance in that specific category.





