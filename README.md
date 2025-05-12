# S&P 500 Stock Price Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

A machine learning project to predict future S&P 500 price movements using historical data and Random Forest classification.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [License](#license)

## Overview
This project:
1. Fetches historical S&P 500 data using Yahoo Finance API
2. Preprocesses and engineers features from the financial data
3. Trains a Random Forest classifier to predict next-day price movements
4. Evaluates model performance using precision scoring

Key insights:
- Predicts whether the S&P 500 will rise (1) or fall (0) the next trading day
- Achieves ~54% precision in predictions
- Focuses on interpretable machine learning approach

## Features
- **Data Collection**: Automated download of S&P 500 historical data
- **Feature Engineering**: 
  - Tomorrow's price target calculation
  - Technical indicators (Open, High, Low, Close, Volume)
- **Modeling**: Random Forest classifier with optimized parameters
- **Evaluation**: Precision scoring methodology

## Installation

1. Clone the repository:
```bash
git clone https://github.com/JuhiGola21/sp500-prediction.git
cd sp500-prediction
