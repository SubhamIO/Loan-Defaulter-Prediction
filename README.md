# Loan Defaulter Prediction

## Problem Statement
- The Bank Indessa has not done well in last 3 quarters. Their NPAs (Non Performing Assets) have reached all time high. It is starting to lose confidence of its investors. As a result, it’s stock has fallen by 20% in the previous quarter alone.
- After careful analysis, it was found that the majority of NPA was contributed by loan defaulters. With the messy data collected over all the years, this bank has decided to use machine learning to figure out a way to find these defaulters and devise a plan to reduce them.
- This bank uses a pool of investors to sanction their loans. For example: If any customer has applied for a loan of $20000, along with bank, the investors perform a due diligence on the requested loan application. Keep this in mind while understanding data.
- In this challenge, you will help this bank by predicting the probability that a member will default.

## Data Acquisition:
- Download the dataset from the following link: https://drive.google.com/drive/folders/15rWe7Mq7BgEyTQ7OZKLK-avJ0L9oveXP?usp=sharing

## Machine Learning task : 
- Binary Classification {Defaulter:1 , Non- Defaulter:0}

## Evaluation Metric:
- Since the data was imbalanced, So , metric used is ROC-AUC

## Approach
- Load data
- Exploratory Data Analysis
- Transform data (data cleansing)
- Handling Missing value 
- Categorize/Dummify
- Split - train and cross validation sets
- Modelling using different models
- Predict
