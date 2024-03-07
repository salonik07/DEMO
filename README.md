# PROJECT

 Machine learning project that predicts campus placement using various classification algorithms. The code includes data loading, exploration, preprocessing, model training, evaluation, and a basic graphical user interface (GUI) for predicting placement based on user input.

Here's a brief summary of the project:
Data Loading and Exploration:

The dataset is loaded using pandas.
The top and bottom rows of the dataset are displayed.
Information about the dataset, including null values and data types, is provided.
Overall statistics of the dataset are presented.
Exploratory Data Analysis (EDA):

The number of students placed is counted.
The top 5 students placed in the Science & Tech field, based on salary, are displayed.
Data Preprocessing:

Irrelevant columns (sl_no and salary) are dropped.
Categorical columns are encoded using mapping.
The dataset is split into features (X) and the target variable (y).
Data is further split into training and testing sets.
Model Training:

Logistic Regression, Support Vector Machine, K-Nearest Neighbors, Decision Tree, Random Forest, and Gradient Boosting classifiers are trained.
Model Evaluation:

Accuracy scores for each model on the test set are calculated and displayed.
A bar plot visualizes the accuracy scores.
Prediction on New Data:

A sample of new data is created.
Logistic Regression is trained on the entire dataset, and predictions are made on the new data.
The probability of placement is displayed.
Model Saving and Loading:

The Logistic Regression model is saved using joblib.
The saved model is loaded and used to make predictions on new data.
GUI Implementation:

A basic Tkinter GUI is created to take user input for various parameters.
Upon clicking the "Predict" button, the model predicts placement probability and displays the result.
