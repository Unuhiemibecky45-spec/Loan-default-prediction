# Loan-default-prediction  

## Overview  
This project predicts the likelihood of loan default using customer and loan history data.   


##  Project Workflow  

1. Problem Statement
   - Financial institutions need to identify high-risk borrowers to minimize loan defaults.  
   - Goal: Build a predictive model to classify borrowers into risk levels.  

2. Data Preparation  
   - Three raw datasets (pro_data_1.csv, pro_data_2.csv, pro_data_3.csv).  
   - Merged and cleaned into clean_master_dataset.csv.  
   - Feature engineering:  
     - Age from birthdate  
     - Repayment delay (days)  
     - Loan active days  
     - Target variable (Good/Bad → 0/1).  

3. Exploratory Data Analysis (EDA) 
   - Loan distributions by size, term days, and repayment delays.  
   - Default rate patterns across demographics and loan sizes.  

4. Model Training 
   - Models compared: Logistic Regression, Random Forest, XGBoost, LightGBM.  
   - Metrics: Accuracy, Precision, Recall, F1, ROC AUC.  
   - Best model: LightGBM (balanced speed & performance).  

5. Model Explainability (SHAP) 
   - SHAP values identify top drivers of loan default risk.  
   - Exported as shap_feature_importance.csv for Power BI.  

6. Power BI Dashboard 
   - KPIs: Accuracy, Default Rate, Total Loans, Avg Probability of Default.  
   - Risk segmentation: High / Medium / Low.  
   - SHAP feature importance visualization.  
   - Loan size vs. default risk analysis.  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1HjMFlD49JBnvoDCDmEtlO36UjTAU_ExR?usp=sharing)
     ##  Repository StructureMachine learning project to predict loan default risk with Power BI
