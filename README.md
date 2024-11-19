# Stock Market Prediction Model

A Python-based machine learning system that predicts NIFTY50 stock price movements using multiple models (Linear Regression, Random Forest, SVR, and LSTM).

## Setup
```bash
pip install numpy pandas scikit-learn tensorflow keras yfinance matplotlib seaborn
```

## Usage
1. Run the main script: `python hope6_paper_finalist1.py` to collect data and generate predictions
2. Run backtester: `python backtester.py` to analyze model performance

Models are evaluated based on win rate and simulated account balance changes, with predictions stored in the `predictions/` directory.

## Disclaimer
For educational purposes only. Not financial advice.
