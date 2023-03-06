# Interconnect-Telecom-Churn-Predictions


## Skills Demonstrated


## Purpose
The telecom operator Interconnect would like to forecast churn of their clients. To ensure loyalty, those who are predicted to leave will be offered promotional codes and special plans. 

## Conclusions
We succeeded in achieving our target AUC ROC score of 0.75. Our final score with the test set is 0.9409, which is roughly 25% more than our target. The boosting models generally had good scores with the training set, but to ensure a better score with the test set, we used a voting classifier. We also looked into the feature importance of the various models in our pipeline, and finally, the important features in our final model. We see that total charges and monthly charges are the most important features, followed by the time frame of the account opening with the year and month. It is reasonable to conclude features such as charges and the length of time a customer has had service, outweigh other factors such as demographics.

Therefore, Interconnect can utilize this model to predict churn. Alongside marketing strategies, the company can target customers likely to leave, and therefore implement strategies to prevent churn. They may also be interested in looking at trends in the charges of customers alongside the length of service, to periodically implement marketing strategies to prevent churn. 