# Credit_Card_Fraud_Detection
ML Project to determine fraudulent activity on credit cards

This is a binary classification problem of detection of fraud / not-fraud credit card activity. In this project we will explore using classical ML as well as neural net such as ANN

Steps on completing the proeject.

1) EDA analysis 
2) It is determined that this is an imbalanced dataset, 99.8% of the data is non-fraudulent.
3) We will fix the imbalance by running SMOTE oversampling of the minority class, but first we have to standardize the dataset. 
4) after oversampling we will run a few ensemble binary classification algorithms such as random forest, XGBoost classifier, Logistic regression, Naive Bayes classifier
5) We will compare results using an Artificial Neural Network.
    - we will optimize the neural network by experimenting with batch-size, epochs, number of layers and neurons in each layer, as well as utilizing learning rate optimizer Adam. We will optimize using GridSearchCV
