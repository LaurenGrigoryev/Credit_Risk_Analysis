# Credit_Risk_Analysis

## Overview of the analysis: 

The purpose of this analysis is to predict credit risk using different resampling techniques to evaluate a credit card dataset from peer-to-peer lending services company LendingClub, and once predicted, to evaluate the models to see whether or not they should be used to predict risk. Since credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans, it is important to test different methods of evaluating the data. For this analysis, I oversampled the data using RandomOverSample and SMOTE algorithms, then I undersampled the data using the ClusterCentroid algorith, and finally I used a combinatorial approach of over- and undersampling the data using the SMOTEENN algorithm. I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 

## Results: 
Below is a breakdown of scores based on accuracy (a ratio of correctly predicted observations to total oberservations), precision (correctly predicted positive observations to the total predicted positive observations), and recall (correctly predicted positive observations to the sum of correctly predicted positive obervations plus false negatives). The definitions are referenced [here](https://blog.exsilio.com/all/accuracy-precision-recall-f1-score-interpretation-of-performance-measures). 

### * RandomOverSample
The balanced accuracy score was .65, while the precision and recall scores were .99 and .58 respectively, [as seen here](https://github.com/LaurenSonis/Credit_Risk_Analysis/blob/main/2021-04-04%20(2).png). Since all of these scores are above .5, we know that this is a fairly accurate model.

### * SMOTE
The balanced accuracy score was .66, while the precision and recall scores were .99 and .69 respectively, [as seen here](https://github.com/LaurenSonis/Credit_Risk_Analysis/blob/main/2021-04-04%20(3).png). Since all of these scores are above .5, we know that this is a fairly accurate model and more accurate than RandomOverSample.

### * ClusterCentroid
The balanced accuracy score was .64, while the precision and recall scores were .99 and .40 respectively, [as seen here](https://github.com/LaurenSonis/Credit_Risk_Analysis/blob/main/2021-04-04%20(4).png). While the accuracy is barely above .5, the recall score is below .5, which makes this a less than ideal model.

### * SMOTEENN
The balanced accuracy score was .54, while the precision and recall scores were .99 and .57 respectively, [as seen here](https://github.com/LaurenSonis/Credit_Risk_Analysis/blob/main/2021-04-04%20(5).png). Since all of these scores are above .5, we know that this is a fairly accurate model.

### * BalancedRandomForestClassifier
The balanced accuracy score was .65, while the precision and recall scores were .99 and .58 respectively, [as seen here](https://github.com/LaurenSonis/Credit_Risk_Analysis/blob/main/2021-04-04%20(6).png). Since all of these scores are above .5, we know that this is a fairly accurate model.

### * EasyEnsembleClassifier
The balanced accuracy score was .65, while the precision and recall scores were .99 and .58 respectively, [as seen here](https://github.com/LaurenSonis/Credit_Risk_Analysis/blob/main/2021-04-04%20(6).png). Since all of these scores are above .5, we know that this is a fairly accurate model.

## Summary: 
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
