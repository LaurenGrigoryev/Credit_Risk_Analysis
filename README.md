# Credit_Risk_Analysis

## Overview of the analysis: 

The purpose of this analysis is to predict credit risk using different resampling techniques to evaluate a credit card dataset from peer-to-peer lending services company LendingClub, and once predicted, to evaluate the models to see whether or not they should be used to predict risk. Since credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans, it is important to test different methods of evaluating the data. For this analysis, I oversampled the data using RandomOverSample and SMOTE algorithms, then I undersampled the data using the ClusterCentroid algorith, and finally I used a combinatorial approach of over- and undersampling the data using the SMOTEEN algorithm. I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 

## Results: 

### * RandomOverSample
The balanced accuracy score was ---, while the precision and recall scores were ----. This means ---.

### * SMOTE
The balanced accuracy score was ---, while the precision and recall scores were ----. This means ---.

### * ClusterCentroid
The balanced accuracy score was ---, while the precision and recall scores were ----. This means ---.

### * SMOTEEN
The balanced accuracy score was ---, while the precision and recall scores were ----. This means ---.

### * BalancedRandomForestClassifier
The balanced accuracy score was ---, while the precision and recall scores were ----. This means ---.

### * EasyEnsembleClassifier
The balanced accuracy score was ---, while the precision and recall scores were ----. This means ---.

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

## Summary: 
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
