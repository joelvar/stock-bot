# StockBot

StockBot is a Python application for designing and testing your own daily stock trading algorithms.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install matplotlib and yfinance from your command line.

```bash
pip install matplotlib
pip install yfinance
```

## Usage
You will be asked to enter a stock ticker for the stock that you want to test the algorithm on.

## Results
After backtesting the moving average algorithm with a buy and hold strategy of the past 15 years, I've noticed that the moving average algorithm has considerable profits for most stocks with starting capital being $1000. Some examples are as follows:

Amazon.com, Inc. : 

Buy and Hold portfolio value: $8040
Returns: $7842

Algorithm portfolio value: $40286
Returns: $40088

NVIDIA Corporation : 

Buy and Hold portfolio value: $10494
Returns: $10166

Algorithm portfolio value: $37356
Returns: $37028

Nike Inc : 

Buy and Hold portfolio value: $6693
Returns: $6099

Algorithm portfolio value: $14286
Returns: $13693

Penumbra Inc:

Buy and Hold portfolio value: $9341
Returns: $7276

Algorithm portfolio value: $13353
Returns: $11288



