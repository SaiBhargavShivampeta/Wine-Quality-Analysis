# Wine-Quality-Analysis

This project aims to predict the quality of wine based on its chemical properties. This dataset has 12 columns, 11 of which are continuous variables that represent the chemical properties of wines, such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, and alcohol. The last column is an ordinal variable that represents the quality of wine, ranging from 1 (worst) to 10 (best). Each variety of wine is tasted by three independent tasters and the final rank assigned is the median rank given by the tasters.

## Data Exploration and Visualization

The first step of this project is to explore and visualize the data to understand its characteristics and distribution. Some of the tasks performed in this step are:

Checking for missing values and imputing them with mean values
Plotting histograms for the continuous variables to see their distribution
Plotting bar charts for the quality variable to see the frequency of each quality level
Plotting scatter plots and correlation matrix to see the relationship between the variables

## Data Preprocessing and Feature Engineering

The next step of this project is to preprocess and transform the data to make it suitable for machine learning models. Some of the tasks performed in this step are:

Scaling the continuous variables using MinMaxScaler to bring them in the range of 0 to 1
Encoding the quality variable as a binary variable, where 0 represents low quality (quality <= 5) and 1 represents high quality (quality > 5)
Splitting the data into training and testing sets with a ratio of 80:20

## Model Development and Evaluation

The final step of this project is to develop and evaluate different machine learning models to predict the quality of wine. Some of the models used in this step are:

Support Vector Classifier (SVC)
Naive Bayes Classifier
Logistic Regression

The performance of each model is evaluated using various metrics, such as accuracy, precision, recall, f1-score, and confusion matrix. The best model is selected based on the highest f1-score on the testing set.
