# Credit Risk Default Modeling

This project predicts **credit card default risk** using **logistic regression** and **bootstrap inference** on the `Default` dataset from the ISLP library. The goal is to estimate the probability of default based on **balance**, **income**, **student status**, and **delinquencies** and evaluate model performance through validation and resampling.

## Overview

* Built logistic regression models to predict default using financial and demographic variables.
* Compared model accuracy using **validation set errors** across multiple train-test splits.
* Implemented **bootstrap resampling** to estimate standard errors of income and balance coefficients.
* Verified that bootstrap and analytical SEs were highly consistent, confirming model stability.

## Key Results

* **Balance** strongly predicts default likelihood.
* Adding **student status** provided minimal accuracy improvement.
* Larger training samples reduced validation error.

## Tools

Python | pandas | NumPy | statsmodels | scikit-learn | ISLP | matplotlib
