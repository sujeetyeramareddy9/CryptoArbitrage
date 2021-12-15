# CryptoArbitrage

Crypto Fun:

- Goal: find the most effective use of Cross-exchange, spatial, and triangular arbitrage to get max profit from n number of curriencies that we choose

Steps:

1. Create accounts, wallet, and how to transfer crypto from one exchange to another
2. Create basic cross-exchange arbitrage algorithm with X list of coins for Binance and Coinbase that produces a profit
   - Web Scraper to find arbitrage and profit on Binance and Coinbase
   - Calculate whether trade is worth it given Currency and Exchange transfer fees
   - TRANSFER FEES: Deposit Fee (exchange A), Withdrawl fee (exchange A), Withdrawl fee (exchange B)
3. Expand algorithm to include more coins as well as more exchanges
4. Include triangular arbitrage and other forms to maximize profits



Algorithm:

Exchange A (BUY)                                           Exchange B (SELL)
BTC 1000                                                   BTC 1005

- max # of shares we can buy that will be filled when sold for price that is profitable (https://www.multitrader.io/cross-exchange-order-book-matching/)
- Things to consider: Transfer fees and buy/sell order fees (filling in full vs not)
