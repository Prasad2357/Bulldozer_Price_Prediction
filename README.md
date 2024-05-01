# Predicting the Sale Price of Bulldozers using Machine Learning

In this notebook, we'll walk through a machine learning project with the goal of predicting the sale price of bulldozers.

## 1. Problem Definition
The task is to predict the future sale price of a bulldozer given its characteristics and historical data on similar bulldozers' sale prices.

## 2. Data
The data is obtained from the Kaggle Bluebook for Bulldozers Competition:
- Train.csv: Training set containing data through the end of 2011.
- Valid.csv: Validation set with data from January 1, 2012, to April 30, 2012. Used to create the public leaderboard.
- Test.csv: Test set containing data from May 1, 2012, to November 2012. Used for final ranking in the competition.

You can find the dataset [here](https://www.kaggle.com/c/bluebook-for-bulldozers/overview).

## 3. Evaluation
The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices. The goal is to minimize the error.

## 4. Features
Kaggle provides a data dictionary detailing the features of the dataset. You can find the data dictionary [here](https://docs.google.com/spreadsheets/d/1WnnQtpGOpwqWAbOu55QSYxQIOG9CFgUKNoqMLa_yx2s/edit#gid=551036337).

Now, let's get started with the analysis!
