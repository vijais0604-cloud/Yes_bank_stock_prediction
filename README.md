# Yes_bank_stock_prediction

## Project Overview

This project focuses on predicting Yes Bank stock prices using Machine Learning techniques. The dataset contains historical stock data including:
	•	Opening Price
	•	High Price
	•	Low Price
	•	Month

The objective of this project is to analyze stock price trends, engineer meaningful features, handle structural market disruptions (specifically the Yes Bank fraud crisis), and build a robust ML model capable of learning changing market patterns.

⸻

## Problem Statement

Stock prices generally follow market-driven patterns influenced by financial performance, investor sentiment, and macroeconomic conditions. However, in the case of Yes Bank, the fraud crisis (2018–2020) significantly disrupted the usual stock behavior, causing extreme volatility and structural pattern changes.

The key challenge of this project was:

How can we build a Machine Learning model that understands both normal market trends and crisis-driven pattern shifts?

⸻

## Dataset Description

The dataset consists of historical monthly stock data of Yes Bank with the following features:
	•	Open – Opening price of the stock
	•	High – Highest price during the month
	•	Low – Lowest price during the month
	•	Month – Time-based feature

From these, additional features were engineered to better capture stock behavior.

⸻

## Feature Engineering

To enhance model performance, multiple derived features were created, such as:
	•	Price range (High − Low)
	•	Volatility indicators
	•	Moving averages
	•	Trend-based features
	•	Crisis period indicator (to help the model distinguish pre-crisis and post-crisis patterns)

Feature engineering played a critical role in helping the model adapt to structural market changes.

⸻

## Handling the Fraud Crisis Impact

The Yes Bank fraud crisis significantly altered historical stock patterns. Instead of treating it as noise, the model was designed to:
	•	Learn pre-crisis trends
	•	Detect volatility shifts during crisis
	•	Adapt to post-crisis recovery patterns

This improved the model’s ability to generalize across different market phases.

⸻

## Machine Learning Approach

Multiple regression models were trained and evaluated to determine the best-performing model. The process included:
	•	Data preprocessing
	•	Train-test split
	•	Model training
	•	Hyperparameter tuning
	•	Performance evaluation

📏 Evaluation Metrics Used
	•	R² Score
	•	Mean Absolute Error (MAE)
	•	Mean Squared Error (MSE)
	•	Root Mean Squared Error (RMSE)

The model with the best performance across these metrics was selected as the final prediction model.

⸻

##Data Visualization & Analysis

Extensive visualizations were created to understand stock behavior and trends, including:
	•	Monthly stock trend plots
	•	High vs Low price comparison graphs
	•	Volatility visualization
	•	Moving average trend graphs
	•	Crisis impact visualization

These visualizations helped in:
	•	Identifying structural breaks
	•	Understanding volatility spikes
	•	Observing long-term trend shifts
	•	Interpreting model behavior

⸻

## Key Insights
	•	The fraud crisis introduced extreme volatility and pattern shifts.
	•	Feature engineering significantly improved predictive performance.
	•	Models trained without considering crisis effects performed poorly.
	•	Time-based and volatility-based features improved robustness.

⸻

## Tech Stack
	•	Python
	•	Pandas
	•	NumPy
	•	Matplotlib
	•	Seaborn
	•	Scikit-learn
