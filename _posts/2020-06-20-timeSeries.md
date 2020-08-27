---
title: "Classes and Function for Time Series Analysis in Python"
last_modified_at: 2020-06-20T16:20:02-05:00
categories:
  - Blog
tags:
  - statistics
  - Python
---

Following my coursework in Time Series Analysis, I regrouped most commonly used methods in a repository.
The file `olsregr.py` implements fundamental methods for linear regression from first principles (in numpy):
fitting the coefficient vector, performing tests on the values of the coefficients and getting confidence intervals, under the assumption of homoskedasticity, heteroskedasticity, or serial correlation in errors.

`timeseries.py` implements common steps of exploratory analysis for time series, from first principles as well: plotting the data and the differentiated data, performing tests for stationarity of the given data series, finding the order of integration of the series, plotting ACFs and PACFs, fitting an AR to the given series.

`timeseriesutils.py` relies on existing packages, and quickly implements common steps in time series analysis: plotting empirical distributions from realizations, performing rolling regressions, testing for some possible violations of OLS hypotheses (multicollinearity, autocorrelation, normality, stability).



You can find the corresponding `GitHub` repository [here][ts_analysis].

[ts_analysis]: https://github.com/GabCaz/timeSeries
