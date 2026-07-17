# Task 1: Retail Sales Forecasting System

## Project Overview
This repository contains a robust predictive framework developed during my Machine Learning Internship to forecast retail demand patterns across multiple product families. The project utilizes structural time-series features and a Linear Regression architecture to model daily sales variations, helping optimization pipelines preemptively understand consumer demand.

## Key Features
* **Data Processing & Feature Engineering**: Developed automated date parsing routines to extract `Year`, `Month`, `Day`, and `DayOfWeek` features alongside categorical one-hot encodings.
* **Exploratory Data Analysis (EDA)**: Implemented four critical data visualization tracks:
  1. *Daily Sales Trend*: Captures macro demand growth and cyclical movement over time.
  2. *Average Sales vs Promotions*: Correlates product promotional volumes against expected velocity increases.
  3. *Top Product Families*: Identifies highest revenue-generating asset categories.
  4. *Forecast Output Visualization*: Maps model inferences onto prospective business windows.
* **Regression Modeling**: Utilizes Scikit-Learn's Linear Regression algorithm optimized to eliminate legacy visualization deprecation warnings.

## Tech Stack
* **Language**: Python
* **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

## How to Run
1. Open the notebook in Google Colab.
2. Execute the code blocks sequentially to generate simulated distributions, evaluate regression parameters, and render targeted line/bar plots.
