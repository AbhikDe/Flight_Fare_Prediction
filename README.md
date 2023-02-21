# Flight Fare Prediction:

<img align="right" width="400" height="400" src="https://github.com/AbhikDe/flight_Fare_Prediction/blob/master/data/Flight-fare-prediction.gif">

## Table of content

* [Problem Statement](#Problem-statement)
* [Goal](#Goal)
* [Approach](#Approach)
* [Dataset](#Dataset)
* [Project Various Step](#project-various-step)
    * [Data Visualization](#data-visualization)
    * [Model Selection](#Model-Selection)
    * [Hyperparameter Optimization](#Hyperparameter-optimization)
    * [Model Dump](#model-dump)
* [Idle used](#idle-used)
* [Model Accuracy](#model-accuracy)
* [Deployed](#Deployed)

## Problem Statement:
Travelling through flights has become an integral part of today’s lifestyle as more and
more people are opting for faster travelling options. The flight ticket prices increase or
decrease every now and then depending on various factors like timing of the flights,
destination, and duration of flights various occasions such as vacations or festive
season. Therefore, having some basic idea of the flight fares before planning the trip will
surely help many people save money and time.

## Goal:
The main goal is to predict the fares of the flights based on different factors available in
the provided dataset.

## Approach:
The classical machine learning tasks like Data Exploration, Data Cleaning,
Feature Engineering, Model Building and Model Testing. Try out different machine
learning algorithms that’s best fit for the above case.

## Dataset:
Dataset link :- [Dataset](https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh)

## Project Various Step:
Data Exploration I started exploring datasets using pandas, NumPy,matplotlib and seaborn.

## Data Visualization
Ploted colleration matrix to get insights about dependend and independed variables. Made chats like( Bocxplot,countplot,distplot,pairplot).

## Model Selection
Made many Models But selected RandomForest Regressor.

## Hyperparameter Optimization
Using Randomizedsearch CV to select the best parameter for training the model

## Model Dump
As per selected trained model is dumped to pickled format for app development

## Idle used
Pycharm

## Model Accuracy
79.84%

## Deployed:
Deployed on heroku -- [Link](https://flight-fare-prediction.herokuapp.com/)
<br> the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Web View:
<img align="center" width="350" height="450" src="https://github.com/AbhikDe/flight_Fare_Prediction/blob/master/Output/demo.jpg">

## Bug / Feature Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an [issue]() here by including your search query and the expected result

## Future Scope
* Use multiple Algorithm
* Optimize Flask app.py
* Front-End
* Sentiment Analysis

# Thanks!!!
