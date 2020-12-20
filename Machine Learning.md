## Hello everyone .. Today we will learn something beautiful and new in our course 401 :fire: :fire: .. Please have fun :blush: :sunglasses: :heart_eyes:

# Bird's Eye View :
* Model - a set of patterns learned from data.
* Algorithm - a specific ML process used to train a model.
* Training data - the dataset from which the algorithm learns the model.
* Test data - a new dataset for reliably evaluating model performance.
* Features - Variables (columns) in the dataset used to train the model.
* Target variable - A specific variable you're trying to predict.
* Observations - Data points (rows) in the dataset.

# Exploratory Analysis :
* Exploratory analysis is about answering questions and extracting insights from your data set, basically getting to know your dataset
* Exploratory analysis for machine learning should be quick, efficient, and decisive
* Start with knowing your direction and answering a set of basic questions about the dataset
* Plot numerical distributions
* Plot categorical distributions
* Plot segmentation (shows you the relationship between categorical features and numeric features)
* Study the correlations between numeric features and other numeric features

# Data Cleaning :
* Remove Unwanted observations.
* Fix Structural Errors.
* Filter Unwanted Outliers.
* Handle Missing Data.

# Feature Engineering :
Feature engineering is about creating new input features from your existing ones.
Using your own or others expertise about the domain can will allow you to engineer informative features
Steps to find new ideas:
Can you create any interaction features that make sense
Combine sparse classes (those that have fewer total observations)
Add dummy variables
Remove unused features

# Algorithm Selection :

Simple linear regression models fit a "straight line" (technically a hyperplane depending on the number of features, but it's the same idea). In practice, they rarely perform well. We actually recommend skipping them for most machine learning problems.

Their main advantage is that they are easy to interpret and understand. However, our goal is not to study the data and write a research report. Our goal is to build a model that can make accurate predictions.

In this regard, simple linear regression suffers from two major flaws:

It's prone to overfit with many input features.
It cannot easily express non-linear relationships.
These flaws can be fixed by the following:

Regularization.
Using Regularized Regression Algos.
Using Decision Tree Algos.
Using Tree Ensembles.

# Model Training :
Building, training and fitting all mean the same thing
When you evaluate your model use test data not the same data you used to train it, because that will result in overfitting
Training sets are used to fit and tune your models. Test sets are put aside as “unseen” data to evaluate your models.
There are two types of parameters in machine learning algorithms:
Model parameters: learned attributes that define individual models
Hyperparameters: “higher-level” structural settings for algorithms
Cross-validation is a method for getting a reliable estimate of model performance using only your training data.
After training you should perform a cross-validation loop on each set of hyperparameter values
Use your test dataset as a means to get a reliable estimate of your model’s performance
To pick the best of your models look at performance, robustness, consistency and weather or not it solves the original problem
