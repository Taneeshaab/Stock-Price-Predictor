# Stock Price Predictor

A deep learning-based stock market forecasting application that predicts future stock prices using **Long Short-Term Memory (LSTM)** networks. The project fetches historical market data from **Alpha Vantage**, performs time-series preprocessing, and trains a PyTorch-based LSTM model to forecast future price movements.

## Features

- Historical stock data retrieval using Alpha Vantage API
- Time-series preprocessing and normalization
- Sliding-window sequence generation for forecasting
- Multi-layer LSTM neural network built with PyTorch
- Train-validation data splitting and model evaluation
- Actual vs Predicted stock price visualization
- Future stock price prediction on unseen data

## Tech Stack

| Component | Technology |
|-----------|------------|
| Programming Language | Python |
| Deep Learning | PyTorch |
| Data Processing | NumPy |
| Data Source | Alpha Vantage API |
| Visualization | Matplotlib |
| Model Architecture | LSTM (Long Short-Term Memory) |

## Project Workflow

```text
Alpha Vantage API
        |
        v
Historical Stock Data
        |
        v
Normalization & Windowing
        |
        v
Train / Validation Split
        |
        v
LSTM Model Training
        |
        v
Price Prediction
        |
        v
Performance Evaluation & Visualization
```

## Key Highlights

- Developed a stock price forecasting pipeline using a 2-layer LSTM architecture for time-series prediction.
- Implemented data normalization, sequence windowing, and train-validation splitting to improve model learning.
- Built an end-to-end deep learning workflow using PyTorch, from data ingestion to prediction and visualization.
- Generated future stock price forecasts and compared actual vs predicted values through interactive plots.

## Installation

```bash
git clone <repository-url>
cd Stock-Price-Predictor
pip install -r requirements.txt
```

## Run

```bash
python project.py
```

## Future Enhancements

- GRU and Transformer-based forecasting models
- Technical indicators (RSI, MACD, Bollinger Bands)
- Streamlit deployment
- Portfolio analytics dashboard
- Real-time stock tracking

## Learning Outcomes

- Time-Series Forecasting
- Deep Learning with PyTorch
- LSTM Networks
- Financial Data Analytics
- Model Evaluation
- Data Visualization

## Disclaimer

This project is intended for educational and research purposes only and should not be used as financial advice.
