# credit-risk-classification
UCI data analytics bootcamp Module 20 Challenge, credit-risk-classification- Ashley Canonizado

- All my code is located within the file 'credit_risk_classification.ipynb'

Analysis Overview:

The purpose of this analysis is to identify the creditworthiness of borrowers. 
The financial data was based on loan size, interest rate, borrower income, their debt to income ratio, number of accounts, deragatory marks, total debt, and lastly loan status. Within the given data, there were about 75036 borrowwers considered healthy loans, and 2500 borrows considered high-risk loans. Pre-given data on every category (X) and loan status (y) was split into two separate categories (X and y), and used to train the machine learning model. Later, test data (similar data, but not within the pre-given data set) was used for a logistic regression model to see if the model's predictions of loan status based on the other categories would reflect what had already been seen with the training data. The model was then evaluated using a confusion matrix and classfication report

Results:

The confusion matrix tells us that there were over 18000 correct predictions within the test model, and less than 1000 incorrect predictions. 
Meanwhile, the classification report gave us the following information:

                precision    recall  f1-score   support

  healthy loan       1.00      0.99      1.00     18765
high-risk loan       0.85      0.91      0.88       619

      accuracy                           0.99     19384
     macro avg       0.92      0.95      0.94     19384
  weighted avg       0.99      0.99      0.99     19384



Summary:

Overall, the classification report tels us that the model is very accurate and lets us know that the logistic regression model is reliable. Both healthy loans (0s) and high-risk loans (1s) are predicted, however as there is less data for high-risk loans- the model is much less accurate in prevision, recall, and the overall f1-score. In that sense, I recommend this model for predicting data with larger sample sizes and more specifically, for healthy loans. It is more important to predict the healthy loans (0s) and the type of data needed to predict is, rather than predicting what type of data makes up a high-risk loan as the sample size given makes results more unpredictable. 

*** All of the work provided in this repository is solely my own, provided by the assignment's start_code, or made with help from the Xpert Learning Assistant. 