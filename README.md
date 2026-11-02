# Volatility Forecasting

Forecasting SPY volatility from 1-minute intraday data, comparing statistical models (statsmodels) with a neural network (PyTorch).

Notebook: `volatility_forecasting.ipynb`

## Data

The 1-minute SPY dataset (`1_min_SPY_2008-2021.csv`, ~140 MB) is too large for GitHub and is not included. Download it and put it in the repo root next to the notebook.

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```
