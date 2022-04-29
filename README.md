1. Set up required packages and dependencies.
```
pip install -r requirements.txt
```
2. Download klines from yfinance API and save to local.
```
export STORE_DIRECTORY=<your desired path>
python download-kline.py -s ETHUSDT BTCUSDT DOTUSDT SOLUSDT -startDate 2017-07-01 -endDate 2022-04-01 -i 1d
```
3. Play around our EDA and trading strategies in jupyter notebooks
