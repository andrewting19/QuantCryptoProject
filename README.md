Abstract 
- Given the pattern of how the price movements in altcoins reacts with the Bitcoin, and investors are most confident in Bitcoin as the least risky crypto, we are pushed to take a step further and analyze our assumption that – when a crypto bears market, following Bitcoin recovers, investors gain confidence to put money in riskier coins so as a result, altcoins may lag behind Bitcoin by a certain amount of time – Lead-lag relationships between alt-BTC and stock-crypto pairings. We will first start by conducting a literature review to see if there’s any historical/ recent findings on such relationships, and we will then perform cross correlation analysis to find such shifts in time and see if there is a significant correlation coefficient. 
Specific to this study, while using cross correlation, we found the max correlation with a timeshift of zero using 1 minute and 1 day data spanning multiple years.

Introduction
- We started with the intent of exploring the relationship between cryptocurrencies. In particular, we expected bitcoin to be a leading indicator of altcoins as it is the largest and most useless crypto. However, we quickly realized that to be minimal, if any. Hence, we shifted to a correlation between crypto assets and stock primarily. Our goal was to be able to trade off of a shift in some indicator that we identify early in the day between a set of possible indicators and assets that can follow those. 

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


Reference: 
1. https://bitcoinist.com/why-has-bitcoin-become-a-leading-indicator-for-the-sp-500/
2. https://www.marketwatch.com/story/bitcoin-is-powerful-but-can-it-predict-nasdaq-and-s-p-500-corrections-and-rallies-11643697587
3. https://markets.businessinsider.com/news/currencies/stocks-highest-correlation-to-bitcoin-ethereum-crypto-ether-jpmorgan-2021-12  
4. https://www.barrons.com/articles/crypto-and-stocks-look-increasingly-correlated-thats-raised-risk-fears-51642207952 
5. https://www.marketwatch.com/story/different-crypto-will-be-less-correlated-as-healthcare-stocks-wont-move-in-the-same-way-gold-etf-moves-a-crypto-asset-manager-says-11642101628 
6. https://towardsdatascience.com/bitcoin-dominance-5a95f0f3319e 
7. https://www.commpro.biz/why-does-bitcoin-have-such-a-big-influence-on-other-cryptocurrencies/ 

