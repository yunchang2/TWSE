# 上市股票每日收盤資訊
Taiwan Stock Exchange Stock Price API

INTRODUCTION

抓取證交所上市公司每日收盤成交資料 ( http://www.tse.com.tw/ch/trading/exchange/STOCK_DAY/STOCK_DAYMAIN.php )。
If you use yahoo's API to get stock prices of TWSE (e.g. quantmod), you probably will get the wrong data. This .R program can help you get the correct stock price and volumn.

GETTING DATA
> source("GetStockPrice.R")
> get_stock_price(uid="0050", start_date="201701")


