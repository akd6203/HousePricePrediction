# Accommodation Price Prediction and Sentiment Analysis

## Overview
This repository contains code for predicting accommodation prices based on various features and conducting sentiment analysis on guest reviews.

## Load Modules
- `numpy`: For numerical operations.
- `pandas`: For data manipulation and analysis.
- `seaborn`, `matplotlib.pyplot`: For data visualization.
- `folium`: For generating maps.
- `sklearn.model_selection.train_test_split`: For splitting the dataset.
- `xgboost.XGBRegressor`: For building the price prediction model.
- `nltk.sentiment.SentimentIntensityAnalyzer`: For sentiment analysis of guest reviews.

## Load the Dataset
- Load the accommodation dataset from 'listings.csv'.

## Task 1: Data Pre-processing
- Select relevant columns that may affect property price.
- Clean the dataset by removing irrelevant columns and dealing with missing values.
- Convert the 'price' column from string to float for further analysis.

## Task 2: Exploratory Data Analysis (EDA) with Data Visualization
- Visualize the distribution of accommodation prices using box plots.
- Plot accommodation distribution on maps.
- Summarize the number of accommodations and mean prices in each region.

## Task 3: Building the Accommodation Prediction Model
- Prepare the dataset by encoding categorical columns.
- Split the dataset into training and testing sets.
- Build an XGBoost regressor model for predicting accommodation prices.
- Evaluate the model's performance using the R^2 score.

## Task 4: Sentiment Analysis
- Load guest reviews dataset from 'reviews.csv'.
- Perform sentiment analysis on guest comments using NLTK's Vader sentiment analyzer.
- Classify reviews as positive or negative based on sentiment scores.

