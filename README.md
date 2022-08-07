# CREDIT RISK ANALYSIS

## Overview

  The purpose of this project is to apply machine learning to solve a real world challenge - credit card risk.
  In this analysis, I used imbalanced-learn and scikit-learn libraries to build and 
  evaluate models using resampling. I used the credit card dataset from LendingClub, I was 
  able to oversample the data using RandomOverSampler and SMOTE algorithms, and undersample the data
  by using ClusterCenteroids algorithms. I also used a combinatorial approach of over and undersampling
  using the SMOTEENN algorithm, then used the BalancedRandomForestClassifier and EasyEnsembleClassifier to predict
  the credit risk. 
  

## Results

   - **_Naive Random OverSampling_**
   
      ![naive random oversampling](https://user-images.githubusercontent.com/103302566/183308753-bfa5146e-982a-4067-baab-34ded81b3ccb.png)
      
      (a) The Balanced Accuracy : 0.6549165830684378
      
      (b) Precision : High for _Low-Risk Loans_ and Low for _High-Risk Loans_.
      
      (c) AVG Recall : 68
      
      

   - **_SMOTE Oversampling_**
    
       ![smote oversampling](https://user-images.githubusercontent.com/103302566/183309020-c3633c63-17c4-40ac-b602-bb3f4a1362f8.png)

      (a) The Balanced Accuracy : 0.6417725241830539
      
      (b) Precision : High for _Low-Risk Loans_ and Low for _High-Risk Loans_.
      
      (c) AVG Recall : 65%
      
      
  - **_Undersampling_**

      ![undersampling](https://user-images.githubusercontent.com/103302566/183309132-df3e404c-a4a4-4511-ad06-c56dcef9a31e.png)
      
      (a) The Balanced Accuracy : 0.6417725241830539
      
      (b) Precision : High for _Low-Risk Loans_ and Low for _High-Risk Loans_.
      
      (c) AVG Recall : 65%
      

        
