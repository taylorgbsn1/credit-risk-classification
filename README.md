# Overview of Analysis
The purpose of this analysis entailed utilizing a dataset encompassing historical lending activity from a peer-to-peer lending services company. The goal was to construct a model capable of assessing the creditworthiness of borrowers. The dataset comprised various variables, including Loan Size, Interest Rate, Borrower Income, Debt to Income Ratio, Number of Accounts, Derogatory Marks, Total Debt, and Creditworthiness. By leveraging the provided variables, the analysis sought to predict a borrower's Creditworthiness. The dataset encompassed 75,036 creditworthy borrowers and 2,500 borrowers classified as risky.

To facilitate the machine learning process, we initially divided the dataset into training data and test data. Subsequently, two Logistic Regression Models were developed: one employing the original dataset, and another utilizing a resampled dataset to ensure a balanced representation of creditworthy and risky borrowers within the training data.


# Results
* Machine Learning Model 1 (Logistic Regression, Unbalanced training data): * Balanced Accuracy Score: 94.31%

   * Creditworthy Borrowers: Precision - 100%, Recall - 100%
   * Risky Borrowers: Precision - 86%, Recall - 89%

* Machine Learning Model 2 (Logistic Regression, Resampled training data so the model is trained on an equal number of creditworthy and risky borrowers):

  * Balanced Accuracy Score (resampled): 99.49%
  * Creditworthy Borrowers: Precision - 100%, Recall - 99%
  * Risky Borrowers: Precision - 86%, Recall - 100%
 
# Summary
The results indicate that the ML Model 2 emerges as the superior choice due to its cautious nature. Our primary objective was to accurately identify the risky borrowers, and ML Model 2, trained on resampled data with an equal representation of creditworthy and risky borrowers, excelled in this task. Notably, it demonstrated remarkable proficiency in identifying risky borrowers while effectively minimizing the instances of falsely identifying creditworthy borrowers.
