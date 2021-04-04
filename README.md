# Udacity Data Scientist Nanodegree Capstone Project
# Starbucks-Capstone-Project
This repository has all the code and report for my Udacity Data Scientist Nanodegree Capstone project.

## Project Overview :
This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.
Not all users receive the same offer, and that was the challenge to solve with this data set.
Our task is to combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type. This data set is a simplified version of the real Starbucks app because the underlying simulator only has one product whereas Starbucks actually sells dozens of products.

## Problem Statement :
Predicting the purchase offer to which a possible higher level of response or user actions like ‘offer received’, ‘offer viewed’, ‘transaction’ and  ‘offer completed’ can be achieved based on the demographic attributes of the customer and other attributes of the companies purchase offers. 

## Installations
This project was written in Python, using Jupyter Notebook on Anaconda. The relevant Python packages for this project are as follows:

- pandas
- numpy
- math
- json
- matplotlib
- seaborn
- sklearn

## File Descriptions
This repo contains 4 files. 
- `Starbucks_Capstone_notebook.ipynb` : the code notebook .
-   `Data` :
    - 1. Profile.json
    - 2. Portfolio.json
    - 3. Transcript.json 

## Reflections
1. I found this project to be challenging as I have never worked with 3 datasets.
2. Most of the time has been spent in cleaning the data and feature engineering.
3. Learned a lot about feature engineering and feature selection.
4. Drew a lot of insights from Exploratory Data Analysis
5. The main goal was to predict the response of the customer based on the offer sent to him.
6. I am satisfied by the predictions made by both the Decision Tree and Random Forest Classifier Models.
7. The F1 Score of both the models on training and testing data sets was way better than the benchmark model.

## Licensing, Authors, Acknowledgements .
Data was provided by Udacity in collobaration with Starbucks. Feel free to use the notebook for your work and research.
