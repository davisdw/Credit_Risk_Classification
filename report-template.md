# Module 12 Report Template

## Overview of the Analysis


Lending companies lend money/properties to borrowers with the expectation that the borrower will either return the asset or repay the lender. Credit Risk is associated with a borrower not returning an asset or paying a loan back causing a lender to lose money. This is measured by lenders in many ways, however in this analysis we will use Machine Learning to analyze a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Using the Machine Learning model To: 

    1. Determine which loans are healthy (low-risk) or non-healthy (high-risk) based on the loan status provided by the lending company.
    2. Find out if the Data Set for loan status are shown as imbalanced 
    3. Compare the Accuracy scores to determine if the prediction is correct and accurate using the following Model: 

          a. **Logistic Regression Model** - widely used to predict the probability of a target variable in classification problems.
          b. If the dataset showing imbalance we're going to use **Random Over Sampler** to re-balance the data 


Also noting will use the confusion matrix to find out if the data showing imbalance and the accuracy of the Data using the LRM (logistic regression model) with the original data and after rebalancing the data 



## Results 

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

===============================

After running the first Logistic Regression Model, the accuracy an 94 % accuracy score, however after running confusion matrix it shows the following dataset : 



<img width="663" alt="Screenshot 2024-02-15 at 10 44 34 PM" src="https://github.com/davisdw/Credit_Risk_Classification/assets/104311388/66c357e2-faf8-40cb-927e-857a8487def0">


[insert data here ]

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
