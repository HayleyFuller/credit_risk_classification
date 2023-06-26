
## Credit Risk Analysis Report

# Overview of the Analysis: 

Credit Risk is often associated with client (borrower) not returning an asset or paying a loan back. This results in the lender loosing money. In this analysis we used machine learning to analyze a dataset of historical lending activity. The historical data is from a peer-to-peer lending services company. The ideal is to build a model that can identify if a client is worthy of a loan. Using various techniques to train and evaluate the model based on loan risk, the following steps were used to come to a final conclusion:

* to split the data into training and testing sets
* create a logistic regression model with the original data
* predict a logistic regression model with resampled training data
* trite a credit risk analysis report.

Using a machine learning model to determine which loans are 'healthy' loans or 'high-risk' loans based on the loan status provided by the lending company.

# Results:

- The accuracy for the Imbalanced data model was 95% acuracy (this could be improved as the data is imbalanced)
- The accuracy for the OverSampled data model was 99% acuracy
- This means the OverSampled data model was a more successful model when analysing data
- For predictions the precision score for the Imbalanced data model was 100% precise for healthy loan status and 85% precise for high-risk loan status
- For predictions the precision score for the OverSampled data model was 100% precise for healthy loan status and 84% precise for high-risk loan satus


# In Summary:

-  A lending company may need a model that requires a way to classifying healthy loans and high-risk loans. 
- The Logistic Regression model with the OverSampled data performed better at 99% than the model with the Imbalanced data at 95% accuracy. 
- Logistic Regession Model 2 is less likely to predict false negative results. However, based on the confusion matrices for each model, Logistic Regession Model 2 predicted more false positives. Which were healthy when the actual was high risk, this could cause a lending company to make 'incorrect' decisions.
- Logistic Regession Model 2 has fewer false predicitions of the data overall and would be the best model to use based on the higher accuracy score.

