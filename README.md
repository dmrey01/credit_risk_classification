# credit_risk_classification
Module 20 Challenge

## Overview of the Analysis

#  During the analysis, a machine learning model was constructed to forecast loan status by utilizing different financial attributes available in the dataset, such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The primary goal was to distinguish between healthy (0) and high-risk (1) loans.

# The process used for the machine learning was as follows: 
Data Preprocessing: Initially, the dataset is imported into the Pandas DataFrame. Subsequently, the data is divided into features (X) and labels (y). Progress is monitored throughout this process. Following the completion of sorting, the data is split into training and testing sets using the "train_test_split" function.

# Machine Learning Model (Logistic Regression): This phase of the analysis pertains to the decision-making aspect. The machine is trained to select the appropriate algorithm for the task at hand. In this scenario, the logistic regression model is chosen as the algorithm. Logistic regression is commonly utilized for binary classification tasks, aiming to predict one of two possible outcomes. It is favored for its simplicity, interpretability, and effectiveness in handling linearly separable data. The decision to opt for logistic regression can be influenced by factors such as the nature of the problem, dataset size and structure, and model interpretability. Logistic regression serves as a solid foundation for classification tasks before delving into more intricate algorithms. Training Data Score and Test Data Scores: Upon completing the  steps as mentioned above, training and testing data scores are obtained. These scores reflect the model's accuracy on both the training and test datasets. Performance metrics, including accuracy, precision, recall, and the confusion matrix, are computed to evaluate the model's effectiveness.



# Machine Learning(ML) Logistic Regression Restuls on Training and Test Datasets: 
        -  Trianing Data Score: 99.29%
        - Testing Data Score: 99.25%
        - Precision and Recall Scores: 
              - Class One (Healthy Loans): Precision = 1.00, Recall = 99%
              - Class Two (High- risk loans): Precision = 0.84, Recall = 94%



* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

   # The evaluation of the logistic regression model's performance on both the training and testing datasets is reflected in the scores provided. These scores allow for the correct classification of instances such as healthy and high-risk loans.

		* Accuracy: The training data achieved a score of 99.29%. This percentage indicates that the model accurately predicted the loan status for 99.29% of the instances in the training dataset, showcasing excellent performance.

		* The accuracy score for the testing data was 99.25%, suggesting that the model accurately predicted the loan status for 99.25% of the instances in the testing dataset.

		* Precision measures the proportion of true positive predictions out of all positive predictions made by the model. In Class One (Healthy loans), the precision score of 1.00 indicates that the model correctly predicted a loan as healthy 100% of the time. In Class Two (High-risk loans), the precision score of 0.84 shows that the model correctly predicted a loan as high-risk 84% of the time.

		* Recall, also known as sensitivity, measures the proportion of true positive predictions out of all actual positive instances in the dataset. For Class One (Healthy loans), the recall score of 99% means that the model correctly identified 99% of all healthy loans in the dataset. For Class Two (High-risk loans), the recall score of 94% indicates that the model correctly identified 94% of all high-risk loans in the dataset.

		* The scores suggest that the logistic regression model performed exceptionally well in predicting loan status. Class One (Healthy loans) achieved perfect precision and very high recall, while Class Two (High-risk loans) showed slightly lower but still strong performance in identifying risky loans.


## Summary
	* The logistic regression model demonstrated remarkable performance in terms of accuracy, precision, and recall scores on both the training and testing datasets. It effectively distinguished between loans categorized as low-risk (Class One) and high-risk (Class Two). The precision and recall values indicate that the model excelled in identifying low-risk loans but had some room for improvement in identifying high-risk loans.

	* Considering the balanced performance across both classes and the high overall accuracy, the logistic regression model appears to be the preferred choice for this task. However, conducting further analysis and exploring alternative algorithms could prove beneficial, particularly if the focus is on enhancing the identification of high-risk loans.
