# Linear Regression Analysis of COVID-19 Data

## Overview

This project applies Linear Regression modeling techniques to analyze the relationship between testing data and confirmed cases of COVID-19, using data from the city of Chicago. The analysis includes both Simple and Multiple Linear Regression models to predict outcomes based on one or more explanatory variables.

## Concept

Linear Regression is a statistical method used to model the relationship between a dependent variable and one or more independent variables. The method is widely used in fields such as finance and investing to predict continuous outcomes. In this project, we focus on two main types of Linear Regression:
- **Simple Linear Regression:** Involves a single explanatory variable.
- **Multiple Linear Regression:** Involves multiple explanatory variables.

The project leverages the Ordinary Least Squares (OLS) method to fit the regression models, and explores both a closed-form solution using the Normal Equation and an iterative optimization approach using Gradient Descent.

## Dataset

The COVID-19 dataset used in this analysis is sourced from public health data released by the city of Chicago. It primarily includes daily counts of tests and confirmed cases.

**Data Source:** [Chicago COVID-19 Daily Testing](https://data.cityofchicago.org/)

## Features

The dataset includes various features, but the primary ones analyzed are:
- `Tests`: Number of COVID-19 tests conducted (independent variable).
- `Cases`: Number of confirmed COVID-19 cases (dependent variable).

Additional demographic features are available and can be explored to understand their impact on the virus spread.

## Installation

To run this analysis, you need to install several Python libraries including Pandas, Numpy, Matplotlib, Seaborn, and Scikit-learn.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn


## Conclusion
This project demonstrates the use of Linear Regression models to understand and predict the dynamics of COVID-19 spread in relation to testing rates. The analysis could be extended by incorporating more features and using more complex models like Polynomial Regression to capture non-linear patterns.