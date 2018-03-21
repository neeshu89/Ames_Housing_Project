# Ames_Housing_Project


## Domain
This problem is drawn from the Ames Iowa Housing dataset from the UCI Machine Learning Database.

This data set has in the past been used to predict the Value of a home given a number of factors, including # of rooms, age, square footage, and quality.

## Problem Statement
For a single home, given knowledge about other attributes of the home, we will be able to use supervised learning to develop a regression model that can predict the value of that home.

We will be particularly interested in understanding the association between `GrLivArea` with `MSSubClass` and `ExterQual`, while also taking into account the `Neighborhood` of the home

## Dataset and inputs
The dataset to be examined contains 80 attributes for 1451 homes sold between 2006 and 2010 in Ames Iowa, including the Sale Price.


## Solution Statement
A solution to this problem will be a regression model such as a linear regression, a decision tree regressor, or a support vector regressor.


## Benchmark Model
Given that we seek a regression model, we will use the mean or median of the Median Home Value as a good naive benchmark.


## Performance Metric
Given that this is a regression task, we can measure the success of our model using the $R^2$ metric, the Mean Absolute Error, or the Mean Squared Error.