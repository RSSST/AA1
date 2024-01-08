# AA1

# Project Overview
Objective: To predict the customer churn for the e-commerce business and identify the main features affected to the customer churn.

SAS e-Miner: This tool used to the process for Sample, Explore, Model and Assess in SEMMA.

Talend Data Intergration: This tool used to combine the dataset.

Talend Data Prep: This tool used to process the data.

# Data File
Dataset1.csv : First dataset
Dataset2.csv : Second dataset
E Commerce Dataset.xlsx : Combined dataset
em_save_TRAIN_Latest Preparation : Processed dataset
* The dataset is self generated and refer to this link as reference : https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction/data 

# Code and Scripts

dataprep_em_save_TRAIN_Latest Preparation_2024-01-07_11-45-40-773 : Code export from the Talend Data Prep of data processing

# Documentation for Each Tool:

SAS e-Miner: Import the dataset into the SAS Enterprise Miner and add the required node for the process to carry out SEMMA

Talend Data Intergration: Import the two dataset into it and use the tMap to combine it and export using the tFileOutputDelimiter.

Talent Data Prep: Upload the combined dataset into it and perform data cleaning.

# Results and Analysis
Gradient Boosting has outperformed compare to the Decison Tree and Random Forest. 	
         **Decision Tree**	**Random Forest**	**Gradient Boosting**
Accuracy	  0.77	           0.79	          0.82
TPR	        0.816	           0.816	        0.816
TNR	        0.737	           0.763	        0.816

# Reflections or Learning Outcomes
The challenges that faced in this project is the data imbalanced problem. By applying with the data oversampling method, it has successfully improved the performance of model in predicting the churn. 


