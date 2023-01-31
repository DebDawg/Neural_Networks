# Charity Analysis

## Overview
  The purpose of the analysis was to create a binary classifier that is capable of predicting which organization applicants will be successful if funded by Alphabet Soup.

## Results

## Data Preprocessing:

  - The Target variable used: "IS_SUCCESSFUL", which indicates if funding will be successful.
  - Variables used as features:
    
    * APPLICATION_TYPE—Alphabet Soup application type
    * AFFILIATION—Affiliated sector of industry
    * CLASSIFICATION—Government organization classification
    * USE_CASE—Use case for funding
    * ORGANIZATION—Organization type
    * STATUS—Active status
    * INCOME_AMT—Income classification
    * SPECIAL_CONSIDERATIONS—Special consideration for application
    * ASK_AMT—Funding amount requested
    * IS_SUCCESSFUL—Was the money used effectively
    
  - Variables removed were:  EIN and NAME—Identification columns

## Compiling, Training, and Evaluating the Model:

  Using 2 hidden layers, 80 Neurons in the first layer and 30 Neurons in the second layer, ReLu activation function for input layers, then Sigmoid for the output layers the following was achieved:
  
  <img width="489" alt="image" src="https://user-images.githubusercontent.com/110787194/215712316-450acce9-c17c-4c17-8b64-7b33a848f3e7.png">  
  
  
  After removing more columns and binning, the target model performance was achieved.
  
 
## Summary: 
 
The Model Performace was below target, I recommend using RandomForest Model because it can perform both regression and classification tasks. It's easier to understand and can handle larger datasets.
