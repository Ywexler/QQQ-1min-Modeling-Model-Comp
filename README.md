Alpha Investing: AIM5005 Strategy Evaluation


Overview
This project was developed by Alpha Investing to assist the NY State Pension Fund in evaluating algorithmic trading strategies for potential internal fund management. The goal is to determine which strategy offers superior performance over a traditional buy-and-hold approach, using SPY ETF data as the test case.
(Note: Alpha Investing is a fictional company)

Objectives
Test and compare multiple algorithmic trading models.
Evaluate models across different feature sets.
Assess strategy performance against a buy-and-hold benchmark.
Provide actionable recommendations based on empirical results.

Data
Source: Yahoo Finance (SPY ETF historical data)

Features engineered:
Simple Moving Averages (SMA)
Exponential Moving Averages (EMA)
Rolling Standard Deviation
Relative Strength Index (RSI)
Volume ratios

Models Tested
Random Forest Classifier
Logistic Regression
XGBoost Classifier
Naive Bayes Classifier

Feature Sets
Base (SMA & RSI)
With EMA
With EMA + Volume

Performance Summary
Model	Base (SMA & RSI)	With EMA	With EMA + Volume
Random Forest	0.15%	0.32%	0.84%
Logistic Regression	-0.06%	0.84%	0.84%
XGBoost	0.66%	0.32%	0.49%
Naive Bayes	0.64%	0.74%	0.68%

Requirements:
matplotlib
numpy
pandas
scikit-learn
xgboost
