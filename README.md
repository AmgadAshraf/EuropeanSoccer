# European Soccer

## Overview and Motivation:
Without a doubt, football has become more than just a game for entertainment in our new era. It has become a huge industry that a lot of people, all around the globe, earn from. More specifically, there are many betting companies nowadays, for the top European leagues in particular, that football lovers take part in by predicting the results of every gameweek's matches. Predictions are, of course, based on numerous factors and statistics, but bettors tend to depend on their personal intuition to make predictions. Rather than merely relying on this, the process can yield more successful results if it is done in an automated way. Thus, the goal of our project is to prepare this European Soccer dataset using the data preprocessing techniques so that it can be fed to a model (e.g. SVM) to predict either a team wins, loses, or draws in a match.   

## Initial Questions:
The first question that raises when attempting to achieve the intended goal is to know which factors contribute to the result of a match, and the proportion that each of them constitutes. 

## Data:
The dataset used in this project is the European Soccer Database from Kaggle.
Link to the database file: https://drive.google.com/file/d/1n-xzgLuV82KGe6Zyr9lKLJqC20gnra9M/view?usp=sharing

## Exploratory Data Analysis:
At first, all the tables in the database were populated to Pandas dataframes. Each dataframe was thoroughly examined to know the necessary data tidying and cleaning procedures that should be applied. Statistical methods as well as visualizations were used to analyze the data and make justifiable decisions. For example, the percentage of missing values in a dataframe was considered to know the appropriate way to impute these missing values. Duplicates were removed in order that the data can serve the aim of our project. Column names and types were investigated to ensure consistency is maintained across all dataframes. All decisions were backed up by statistical means.

## Final Analysis:
After all the dataframes were cleaned, some dataframes were merged to obtain meaningful results that can be used to feed a machine learning model to predict a match outcome. A match lineups visualization is shown at the end of this notebook, illustrating a match between Barcelona vs Real Madrid, displaying the home and away team names, and the season when this match was held. Each team formation in this match is presented in a different colour, displaying the name of the player occupying each position in the football field along with his latest overall rating.

![Screenshot](https://github.com/AmgadAshraf/EuropeanSoccer/blob/master/Pitch%20Visualization.png)
