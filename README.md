Personal Project: Fraud Detection in Credit Card Transactions

I'm excited to share my personal project on detecting fraudulent credit card transactions to prevent financial losses and protect customers. 🚀

Objective: Detect fraudulent credit card transactions to prevent financial losses and protect customers.

Steps Involved:

Data Collection and Preprocessing: I used a dataset of credit card transactions and addressed the data imbalance issue using SMOTE and other techniques.

Handling Imbalanced Data: I applied oversampling and undersampling techniques to ensure a balanced dataset.

Feature Engineering: I created new features to capture transaction patterns and applied scaling and normalization techniques.

Model Building: I tested several models, including:

Logistic Regression: 89.0% accuracy score
K-Nearest Neighbors (KNN): 95.0% accuracy score
Support Vector Classifier (SVC): 95.0% accuracy score
Decision Tree Classifier: 84.0% accuracy score
Model Evaluation: I evaluated the models using metrics such as Precision, Recall, F1 Score, and AUC-ROC, with a focus on minimizing false negatives.

Implementation: I implemented a real-time transaction monitoring system that flags suspicious activities. Additionally, I developed a system for ongoing model updates and retraining to ensure the model remains accurate and effective over time.

Model Selection: After training the models using GridSearch, I evaluated their performance on different metrics. Here are the results:

svc : The Support Vector Classifier (SVC) with a regularization parameter C=0.5 performed the best. 
LogisticRegrestion :The Logistic Regression model with a regularization parameter C=0.001 performed second best 
tree_clf : The Decision Tree Classifier with a maximum depth of 2 and a minimum of 5 samples per leaf node performed third best. 
KNeighborsClassifier : The K-Nearest Neighbors Classifier with 2 neighbors performed the worst add these informations in last

