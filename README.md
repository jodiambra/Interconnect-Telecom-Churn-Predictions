# Interconnect-Telecom-Churn-Predictions

![1_OV8OjU1ll5QDxD0Yet23Nw](https://user-images.githubusercontent.com/115895428/223225269-74f410fa-3eab-4f6c-ab4f-dc95bbfa8b6a.png)


## Skills Demonstrated
    Pandas
    Numpy
    Plotly Express
    Profile Report
    OneHot Encoding
    Grid Search CV
    Classification Models
    Boosting
    SMOTE
    Pipeline
    AUC
    ROC AUC

## Purpose
The telecom operator Interconnect would like to forecast churn of their clients. To ensure loyalty, those who are predicted to leave will be offered promotional codes and special plans. 

## Conclusions
We succeeded in achieving our target AUC ROC score of 0.75. Our final score with the test set is 0.9409, which is roughly 25% more than our target. The boosting models generally had good scores with the training set, but to ensure a better score with the test set, we used a voting classifier. We also looked into the feature importance of the various models in our pipeline, and finally, the important features in our final model. We see that total charges and monthly charges are the most important features, followed by the time frame of the account opening with the year and month. It is reasonable to conclude features such as charges and the length of time a customer has had service, outweigh other factors such as demographics.

Therefore, Interconnect can utilize this model to predict churn. Alongside marketing strategies, the company can target customers likely to leave, and therefore implement strategies to prevent churn. They may also be interested in looking at trends in the charges of customers alongside the length of service, to periodically implement marketing strategies to prevent churn. 


## Figures

ADA Boost Feature Importance: https://rawcdn.githack.com/jodiambra/Interconnect-Telecom-Churn-Predictions/db49a3e819ea0ff7f814c42059b5924885cd058e/figures/fig1.html

XG Boost Feature Importance: https://rawcdn.githack.com/jodiambra/Interconnect-Telecom-Churn-Predictions/a00182ee4ca6eed8b8ac098e077d3fc1185a9619/figures/fig2.html

Light GBM Feature Importance: https://rawcdn.githack.com/jodiambra/Interconnect-Telecom-Churn-Predictions/a00182ee4ca6eed8b8ac098e077d3fc1185a9619/figures/fig3.html

Gradient Boost Feature Importance: https://rawcdn.githack.com/jodiambra/Interconnect-Telecom-Churn-Predictions/a00182ee4ca6eed8b8ac098e077d3fc1185a9619/figures/fig4.html

Cat Boost Feature Importance: https://rawcdn.githack.com/jodiambra/Interconnect-Telecom-Churn-Predictions/a00182ee4ca6eed8b8ac098e077d3fc1185a9619/figures/fig5.html

Model Comparison: https://rawcdn.githack.com/jodiambra/Interconnect-Telecom-Churn-Predictions/a00182ee4ca6eed8b8ac098e077d3fc1185a9619/figures/fig6.html

ROC Curve: https://rawcdn.githack.com/jodiambra/Interconnect-Telecom-Churn-Predictions/a00182ee4ca6eed8b8ac098e077d3fc1185a9619/figures/fig7.html

Top 10 Features: https://rawcdn.githack.com/jodiambra/Interconnect-Telecom-Churn-Predictions/a00182ee4ca6eed8b8ac098e077d3fc1185a9619/figures/fig8.html
