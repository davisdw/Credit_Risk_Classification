# Module 12 Report Template

## Overview of the Analysis


Lending companies lend money/properties to borrowers with the expectation that the borrower will either return the asset or repay the lender. Credit Risk is associated with a borrower not returning an asset or paying a loan back causing a lender to lose money. This is measured by lenders in many ways, however in this analysis we will use Machine Learning to analyze a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Using the Machine Learning model To: 

    1. Determine which loans are healthy (low-risk) or non-healthy (high-risk) based on the loan status provided by the lending company.
    2. Find out if the Data Set for loan status are shown as imbalanced 
    3. Compare the Accuracy scores to determine if the prediction is correct and accurate using the following Model: 

        a. Logistic Regression Model - widely used to predict the probability of a target variable in classification problems.
        b. If the dataset showing imbalance we're going to use Random Over Sampler to re-balance the data 


Also noting will use the confusion matrix to find out if the data showing imbalance and the accuracy of the Data using the LRM (logistic regression model) with the original data and after rebalancing the data 



## Results 

After running the first Logistic Regression Model, the accuracy an 94 % accuracy score, however after running confusion matrix it shows the following dataset : 



<img width="663" alt="Screenshot 2024-02-15 at 10 44 34 PM" src="https://github.com/davisdw/Credit_Risk_Classification/assets/104311388/66c357e2-faf8-40cb-927e-857a8487def0">


The data 0 (for healthy Loan ) shows comprised dataset support of 18759 while the data 1 (for high risk) shows dataset support of 625 which indicated that they're is an major imbalance in the dataset 

noted that precision, recall and f-score showing 1.0 for healthy loan data

After using the RandomOverSampler module from the imbalanced-learn library the data was updated as follows: 


<img width="765" alt="Screenshot 2024-02-15 at 11 01 18 PM" src="https://github.com/davisdw/Credit_Risk_Classification/assets/104311388/4aa8f07a-8c75-4891-ba15-fd8376396e8b">


Noticed the high risk loan dataset has increased in the recall score of 1.0 and f1-score has also increased to 0.93 

Also the accuracy score has increased to 99% after using the imbalance model 


## Summary

Using the LRM and comparing the dataset before and after the Re-Balance which in-fact improved the accuracy of the Logistic Regression Model, this can be used when they're is insufficent amount of features or classification that the data model relies on. In short they're also risk of potentially making the data biased resulting in overfitting 
