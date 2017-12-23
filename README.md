# McAfeeCryptoBot
Algo to pump and dump cryptos

use REST API TWITTER: 
-Get for every tweet from mcafee
-parse (every spcae delimeter) for ticker and name
-validate existence of this crypto currency

use REST API BITTREX/BINANCE (pick one with more breadth):
- use get to get all the tickers/names, set them to constant variables
- once validated mcafee tweeted a ticker: make a PUT request to buy x amount of crypto and limit sell at y% change


