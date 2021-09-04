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

# Metrics
I will choose the following strategy —
a) Performing the initial EDA to analyse the data.
b) Applying the different statistics to have a deep dive into the datasets.
c) Applying the different machine learning models and then choosing best ML model based on the precision, recall, F1-score.
d) Performing the final EDA to view the merged datasets in the combined way (as per our problem statement overview section).

# Implementation 
In this section, I need to start with the defining the variables X and Y from the cleaned merged dataset, I have used the following columns to ‘time’,’difficulty’,’duration’,’reward’,’offer_type_number’,’age_group_number’,’income_group_number’,’gender_group_number’ to be put in the variable X
Y variable would be the event.
This is important step to our initial problem statement so as to keep track of the starting data analysis where in we need to make sure that the steps which are undertaking are correct and we should not deviate from our problem statement, we are trying to find the answers for predicting the response of the customer to an offer ‘viewed’ or ‘completed’ by the customer on the Starbucks app.
Splitting the data into the test and train based on 33% test size and then using the Min Max Scaler to fit the transformation that will normalize the features hence the increasing the accuracy of the classifier

# Reflection
I started with the initial data analysis of the three given datasets by the Starbucks — i.e. portfolio, profile and transcript, in our initial Exploratory Data Analysis I have found that the Portfolio dataset is clean and easy understandable with no null values, Profile dataset is very unformatted and needs data cleaning before I do some data modelling using ML models. I have found this most difficult part.
Transcript dataset is also very tricky where offer id are encoded and encrypted due to the security purposes.
After data wrangling and cleaning, most interesting to test and compare the different ML models to predict on which offer customer will response more appropriately.

# Improvements
In my view, user-user recommendations can be built further for our Starbucks App so that the customer can see their best offers according to the filters they choose on the app but before that our initial input file data needs to be handled in more efficient way because choosing and then comparing the ML models is mostly time consuming, Hyper Parameter Tuning can be further used to identify the features which are to be choose to built this in future.

# Files used in this Repository 

Following are the files these contains the Python code used for this Capstone Project
- Starbucks_Capstone_notebook.ipynb
- Starbucks_Capstone_notebook.html


# Motivation
I have completed this project as a part of the Udacity Data Science Nanodegree Program - Starbucks Capstone Challenge.

# Medium Blog 
https://aseemnarula.medium.com/starbucks-capstone-challenge-f8ea3a80424e

# References

**Classification Report**
https://scikit-learn.org/stable/modules/generated/sklearn.metrics.classification_report.html

**Grid Search CV**
https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html
https://www.kaggle.com/enespolat/grid-search-with-logistic-regression

**Metrics Used**
https://machinelearningmastery.com/tour-of-evaluation-metrics-for-imbalanced-classification/
https://medium.com/r/?url=https%3A%2F%2Fmachinelearningmastery.com%2Ffailure-of-accuracy-for-imbalanced-class-distributions%2F

**K-Fold Cross Validation & Grid Search Hyper Parameter Tuning**
https://stackabuse.com/cross-validation-and-grid-search-for-model-selection-in-python/


