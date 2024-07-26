# Titanic Survival Prediction

This repository contains a solution to the classic Titanic dataset problem. The goal is to predict whether a passenger survived the Titanic disaster based on various features such as age, sex, class, etc.

# Table of Contents
- Dataset
- Installation
- Evaluation
- Tuning
- Prediction
- Submission
- Contributing
- License
- Dataset

# Dataset
The Titanic dataset can be downloaded from the Kaggle Titanic Competition.

# Model Building
The model building process involves the following steps:

- Load the Data: Load the training and test datasets using Pandas.
- Explore the Data: Examine the data to understand its structure and summary statistics.
- Preprocess the Data: Handle missing values.
- Convert categorical variables into numerical ones.
- Drop irrelevant features.
- Split the Data: Split the training data into training and validation sets.

# Evaluation
The model's performance is evaluated using accuracy on the validation set. Additional metrics such as precision, recall, and F1-score can be added for a more comprehensive evaluation.

# Tuning
Hyperparameter tuning is performed using 'GridSearchCV' to find the best parameters for the RandomForestClassifier. The parameters grid includes:

- n_estimators: Number of trees in the forest.
- max_features: Number of features to consider when looking for the best split.
- max_depth: Maximum depth of the tree.
- criterion: Function to measure the quality of a split.

# Prediction
Once the model is trained and tuned, it is used to predict the survival status of passengers in the test set. The predictions are saved in a (submission.csv) file.

# Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
