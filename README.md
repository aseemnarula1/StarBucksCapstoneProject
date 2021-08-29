# StarBucksCapstoneProject
Udacity StarBucks Capstone Project

# Introduction
My name is Aseem Narula, a RPA consultant (….in simple words we make software bots using UiPath….) and a aspiring Data Scientist currently enrolled and pursuing my journey by learning with the Udacity Data Science Nanodegree. This project would be my last Capstone project where I would be using my Data Science and Machine Learning skills to analyse the problem from the given dataset and will present the ML solution to tackle the business problem for the Starbucks.

# Project Overview
This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.

# Problem Statement
The three main datasets are as follow —
portfolio.json — containing offer ids and meta data about each offer (duration, type, etc.)
profile.json — demographic data for each customer
transcript.json — records for transactions, offers received, offers viewed, and offers completed
***JSON is file format of the input source data***
Our main goal is to combine the above three datasets — Portfolio, Profile and Transcript i.e. combining transaction, demographic and offer data to determine which demographic groups respond best to which offer type.
I will also build ML model from the given dataset to predict the response of a customer to an offer which is either completed or viewed.
Metrics
I will choose the following strategy —
a) Performing the initial EDA to analyse the data.
b) Applying the different statistics to have a deep dive into the datasets.
c) Applying the different machine learning models and then choosing best ML model based on the precision, recall, F1-score.
d) Performing the final EDA to view the merged datasets in the combined way (as per our problem statement overview section).


# Motivation
I have completed this project as a part of the Udacity Data Science Nanodegree Program - Starbucks Capstone Challenge.

# References

**Classification Report**
https://scikit-learn.org/stable/modules/generated/sklearn.metrics.classification_report.html

**Grid Search CV**
https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html
https://www.kaggle.com/enespolat/grid-search-with-logistic-regression


