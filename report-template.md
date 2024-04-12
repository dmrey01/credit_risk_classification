# Module 20 Report Template
SEE READ ME For results 
## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

            * Explain the purpose of the analysis.
            * Explain what financial information the data was on, and what you needed to predict.
            * Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
            * Describe the stages of the machine learning process you went through as part of this analysis.
            * Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

## Results

# 

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

# The logistic regression model achieved outstanding results with high accuracy, precision and recall socrs on both training and testing data.  It effectively distingusihed between health and high-risk loans.  The precision and recall values suggest that the model performed exceptionally well in identifying health loans (Class -One) but, showed some room for improvement in identifying high-risk loans (Class Two).

Considering the balnaced performance across both classes and the high overall accuracy, the logistic regression model appears to be the prefered choice for this task.  However, further analysis and possible the exploraiton of the other algorithms could be beneficials, especially if the empahsis shifts towards improving the identifications of high- risk loans. 