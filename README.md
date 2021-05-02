# Machine Learning Homework - Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, machine learning models were generated capable of classifying candidate exoplanets from the raw dataset.

Tasks performed in this challenge:

1. [Preprocess the raw data](#Preprocessing)
2. [Tune the models](#Tune-Model-Parameters)
3. [Compare two or more models](#Evaluate-Model-Performance)

- - -

## Instructions

### Preprocess the Data

* Preprocess the dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features.
* Use `MinMaxScaler` to scale the numerical data.
* Separate the data into training and testing data.

### Tune Model Parameters

* Use `GridSearch` to tune model parameters.
* Tune and compare at least two different classifiers.

- - -

## Resources

* [Exoplanet Data Source](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)

* [Scikit-Learn Tutorial Part 1](https://www.youtube.com/watch?v=4PXAztQtoTg)

* [Scikit-Learn Tutorial Part 2](https://www.youtube.com/watch?v=gK43gtGh49o&t=5858s)

* [Grid Search](https://scikit-learn.org/stable/modules/grid_search.html)

- - -

## Considerations

* Start by cleaning the data, removing unnecessary columns, and scaling the data.

* Not all variables are significant be sure to remove any insignificant variables.

* Make sure your `sklearn` package is up to date.

* Simple model first, and then tune the model using `GridSearch`.

* When hyper-parameter tuning, some models have parameters that depend on each other, and certain combinations will not create a valid model. Be sure to read through any warning messages and check the documentation


# Reporting

* From the machine learning models used to analyze the raw data, Random Forest ML model had the highest testing data score. 

## Model Scores

### Logistical Regression 
    Training Data Score: 0.806790005721915
    Testing Data Score: 0.8197940503432495

### Decision Tree Classifier
    Testing Data Score: 0.8638443935926774

### Random Forest
    Testing Data Score: 0.9073226544622426

### SVC
    Training Data Score: 0.8033568567613961
    Testing Data Score: 0.8232265446224256
    
    With Hyperparameter Tuning
    Testing Data Score: 0.8136522242193583



- - -