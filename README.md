
# Credit Card Fraud Detection Model

This repository contains a credit card fraud detection model that uses machine learning algorithms to detect fraudulent transactions. The model was built using the Python programming language and scikit-learn library.

The dataset used for training and testing the model is the Credit Card Fraud Detection dataset from Kaggle. The dataset contains credit card transactions a total of 284315 transactions, of which 492 (0.17%) are fraudulent.


The model uses a supervised learning algorithm called Random Forest Classifier to classify transactions as either fraudulent or non-fraudulent. SMOTE is used to handle imbalanced datasets like the credit card fraud dataset.

The model achieved an accuracy of 99.98%, precision of 99.97%, and recall score was 1 on the test set.




### Deployment
Inorder to deploy the fraud detection model, I have used streamlit:

Put all the V1-V28 features along with the amount(Normalized value) and predict whether it is a fraudulent or a legitimate transactions.

V1-V28: may be result of a PCA Dimensionality reduction to protect user identities and sensitive features








![alt text](https://img.shields.io/badge/Python-3.11-orange)

![alt text](https://img.shields.io/badge/Streamlit-Share-brightgreen)
###  Acknowledgements

The dataset used in this project was obtained from Kaggle.
The code for this project was inspired by the Credit Card Fraud Detection project by Data Flair.

https://www.youtube.com/watch?v=239TaYSQI-s&t=1440s

Feel free to contribute to the project by opening pull requests or creating issues if you encounter any problems