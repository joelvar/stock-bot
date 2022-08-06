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
After backtesting the moving average algorithm(starting capital being $1000) with a buy and hold strategy of the past 15 years, I've noticed that the moving average algorithm has considerable profits for most stocks. Some examples are as follows:

Amazon.com, Inc. : 

Buy and Hold Strategy Returns: $7842

Moving Average Strategy Returns: $40088

![AMZN](https://github.com/joelvar/stock-bot/blob/master/Images/amzn.PNG?raw=true)

NVIDIA Corporation : 

Buy and Hold Returns: $10166

Moving Average Strategy Returns: $37028

![NVDA](https://github.com/joelvar/stock-bot/blob/master/Images/nvda.PNG?raw=true)

Nike Inc : 

Buy and Hold Returns: $6099

Moving Average Strategy Returns: $13693

![NKE](https://github.com/joelvar/stock-bot/blob/master/Images/nke.PNG?raw=true)

Penumbra Inc:

Buy and Hold Returns: $7276

Moving Average Strategy Returns: $11288

![PEN](https://github.com/joelvar/stock-bot/blob/master/Images/pen.PNG?raw=true)


