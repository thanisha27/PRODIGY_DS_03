# PRODIGY_DS_03
Task: Build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. use a dataset such as the bank marketing dataset from the UCI machine learning repository.

 Steps:

- Importing Libraries

- Loading Data

- Data Exploration

- Target Variable Analysis :Creates a count plot of the 'deposit' column, which appears to be the target variable.

- Encoding Target Variable: The code converts the 'deposit' column into binary format ('yes' -> 1, 'no' -> 0) to prepare it for classification.

- Feature Analysis: The code analyzes several categorical features in the dataset using count plots to understand the distribution and the relationship with the 'deposit' variable.

- Correlation Analysis : The code selects numeric columns and creates a correlation matrix to analyze the relationships between these numeric features. It displays the correlation matrix as a heatmap and a pair plot.

- Preparing Data for Classification :The code encodes categorical features using one-hot encoding, converting them into binary format for machine learning.

- Model Building: The code splits the data into training and testing sets using train_test_split.
It creates a DecisionTreeClassifier with a random state of 42 and fits the classifier to the training data.

- Model Evaluation :The code makes predictions on the test data using the trained model.
It calculates the accuracy score, confusion matrix, and classification report for the model's performance.
It also visualizes the decision tree using plot_tree.

- Display Results: The accuracy, confusion matrix, and classification report are displayed in the console.

The primary goal of this code is to load, explore, preprocess, and analyze the dataset, and then build and evaluate a decision tree classifier to predict the 'deposit' variable (likely indicating whether a customer will make a deposit or not). The script provides insights into the dataset's features and the model's performance.
