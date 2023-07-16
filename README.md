# Classify Meister

## Introduction

Classify Meister is a Python script that performs classification analysis on the Titanic dataset. It utilizes machine learning techniques, specifically logistic regression, to predict survival outcomes based on various features such as passenger class, age, gender, and fare.

## Prerequisites

To run the script, make sure you have the following libraries installed:

- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

## Dataset

The script uses the "train.csv" file as the dataset, which contains information about passengers on the Titanic. The dataset is loaded using the Pandas library.

## Exploratory Data Analysis (EDA)

The script begins with some EDA to gain insights into the dataset. It performs the following operations:

- Displays the length of the dataset.
- Shows the first few rows of the dataset.
- Provides descriptive statistics of the dataset.
- Displays the column names of the dataset.
- Prints the information and data types of each column.

## Visualization

The script utilizes various visualization techniques to understand the data better. It creates the following plots:

- Count plot of the "Survived" column to visualize the distribution of survival outcomes.
- Count plot of "Survived" with respect to "Sex" to examine the survival distribution by gender.
- Histograms of the numerical columns to visualize their distributions.
- Boxplots of the numerical columns to identify outliers.
- Heatmap of the correlation matrix to visualize the relationships between numerical features.

## Data Preprocessing

The script performs data preprocessing to handle missing values and prepare the data for classification. The following steps are taken:

- Checking for missing values in the dataset.
- Displaying a heatmap to visualize the missing values.
- Replacing missing values in the "Age" column with the mean value.
- Dropping the "Cabin" column due to a high number of missing values.

## Classification

The script performs logistic regression for classification. It carries out the following steps:

- Dividing the dataset into input features (X) and the target variable (Y).
- Splitting the data into training and testing sets using the train_test_split function.
- Creating an instance of the LogisticRegression model.
- Fitting the model to the training data.
- Making predictions on the test data.
- Generating a confusion matrix to evaluate the model's performance.
- Displaying a classification report, which includes precision, recall, F1-score, and support metrics.

## Conclusion
Classify Meister is a Python script that utilizes logistic regression to classify survival outcomes based on Titanic passenger data. By following the steps outlined in the script, you can gain insights into the dataset, preprocess the data, and train a logistic regression model for classification.

For any questions or further information, please contact: 
- Email: ck32266@gmail.com
