 Predicting the sale Price of Bulldozers using Machine Learning
 
In this notebook we're going through an example machine learning project with the goal of predicting the sale price of bulldozers.

Problem Defination: 
How well can we predict the future sale price of bulldozers, given it's charactersticts and previous examples of how much bulldozer have been sold for?

Data: 
The data is downloaded from Kaggle Blue Book for buldozers competition: https://www.kaggle.com/c/bluebook-for-bulldozers/data

These are the three main datasets:

Train.csv is the training set, which contains data through the end of 2011.

Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.

Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.

Evaluation The evaluation metric for this competition is the RSMLE (root mean squared log error) between the actual and predicted auction prices.
For more on the evaluation for this project https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation

Note: The goal for the most regression metrics is to minimize the error. For example: our goal for this project will be to build a machine learning model which minimises RSMLE.

Features
Kaggle provides a data dictionary detailing the features of the dataset. You can view this data dictionary in the various Google Sheets. https://docs.google.com/spreadsheets/d/18lybLR8sbDJLITkWG7ozKM8I3RyieQ2Fpgix-beSYI/edit?usp=sharing
