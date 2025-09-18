# Rolling-Lasso-factor-model
Overview

This project implements a rolling Lasso/Elastic Net framework to predict cross-sectional stock returns.
It integrates feature selection, out-of-sample evaluation, and portfolio backtesting, providing a full pipeline for factor research.

Key Features

Data preprocessing: cleaning, winsorization, standardization, optional industry/size neutralization

Rolling Lasso/Elastic Net regression: 60-month training windows with time-series CV to select hyperparameters

Dynamic feature selection: automatically identifies predictive factors each month

Signal evaluation: monthly IC/ICIR analysis and positive-IC ratio

Portfolio backtest: quantile long–short (Q10–Q1) strategy, cumulative return, IR, drawdown

Factor stability: frequency analysis of selected features

Results

Achieved positive mean IC and stable ICIR over the test period

Long–short portfolios (Q10–Q1) generated consistent cumulative returns

Factor selection logs show momentum, size, and quality features being most frequently chosen
