## Credit Card Fraud Detection

**It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.**
**The dataset contains transactions made by credit cards in September 2013 by European cardholders.**
**This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.**

**It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.**\
# Features:
Data Collection: Gathering a comprehensive dataset containing credit card transactions, including both legitimate and fraudulent instances, to train and evaluate the model. \
Data Preprocessing: Cleaning and preprocessing the dataset, handling imbalanced data, and scaling features to prepare the data for model development. \
Exploratory Data Analysis (EDA): Conducting exploratory analysis and visualization to understand patterns, trends, and anomalies within the transaction data. \
Model Development: Employing various machine learning algorithms such as Logistic Regression, Random Forest, or Gradient Boosting to create a predictive model capable of distinguishing between genuine and fraudulent transactions. \
Model Evaluation: Evaluating model performance using metrics like precision, recall, F1-score, and AUC-ROC to assess the model's accuracy in detecting fraudulent activities.
# Technologies Used:
Programming Languages: Python
Libraries: Pandas, NumPy, Scikit-learn
Machine Learning Techniques: Supervised Learning, Imbalanced Data Handling, Model Evaluation

Kaggle Dataset:https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
