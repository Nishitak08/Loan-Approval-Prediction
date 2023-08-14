# Loan-Approval-Prediction

## Problem Background and Motivation
The project aims to automate the loan eligibility process for banks based on customer details provided in online application forms. By analyzing factors like Gender, Marital Status, Income, Credit History, and more, the project helps banks make informed decisions on loan approvals.

## Import Packages
This section imports necessary Python packages for data manipulation, visualization, and machine learning. It utilizes libraries like Pandas, SKLearn, Matplotlib, Seaborn, and Plotly to perform various tasks such as data loading, data splitting, model fitting, and result visualization.

## Custom Functions
The custom function in this section is used to display performance measures for machine learning models. It calculates metrics such as True Positive (TP), True Negative (TN), False Positive (FP), False Negative (FN), Precision, Recall, Accuracy, and more. This function aids in evaluating model performance across different probability threshold values.

## Data Extraction
This section loads the loan approval dataset and performs an initial evaluation. It identifies the target variable ('approved') and explores the columns and their definitions. It also provides information about the number of records and columns in the dataset.

## Data Exploration and Transformation
This part focuses on data exploration and transformation. It covers steps such as initial cleanup, outlier detection and treatment, feature selection, and data partitioning. The dataset is analyzed for missing values, duplicates, and outliers. Selected features are normalized using Z-Scores. These preprocessing steps ensure that the data is suitable for building machine learning models.

## Machine Learning Model - Logistic Regression
In this section, a Logistic Regression model is trained on the preprocessed data. The model's accuracy is evaluated on both training and testing data. The ROC curve is plotted to visualize the model's performance. A threshold is chosen based on the ROC curve and corresponding performance measures are calculated for that threshold.

## Machine Learning Model - K-Nearest Neighbors (KNN)
This section involves training a K-Nearest Neighbors (KNN) classifier for various values of k. The accuracy of the model is measured for each value of k. The best value of k is determined based on the highest accuracy achieved. The chosen k value is then used to train the final KNN model, and its accuracy is evaluated.

## Performance Metrics and Model Selection
The final models (Logistic Regression and KNN) are evaluated using various performance metrics. The emphasis is on minimizing false negatives to ensure that eligible loan applications are not rejected. The performance metrics are analyzed for different probability threshold values. A threshold that balances precision and recall is chosen to make decisions about loan approvals.

