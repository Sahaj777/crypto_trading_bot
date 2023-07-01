# Algorithmic Trading Bot

This is a trading script that uses alpaca trading to initiate paper trades.

WHAT IT DOES: 
    Gets a list of qualified stocks and submits an order to buy 100 quantities of each, at 10% under market price. 
    Wait 3 seconds after each other to ensure it has enough time to complete the order.

WHICH SYMBOLS QUALIFY:
    The script searches Yahoo finance trending symbols and determines if the stock is qualified based on two factors:
    1 - The crypto must have a change percentage greater than 5%
    2 - The crypto must have a market price below $100

WHERE IT GETS DATA FROM:
    crypto data is retrieved from yahoo finance.
    crypto data is received as real-time data from IEX (the Investors Exchange)
    
TO USE THIS SCRIPT:
    You have to sign up for alpaca free trading account: https://alpaca.markets/docs/trading-on-alpaca/market-data/
    And get an API key and secret from the paper trading tab which you can save to your environment variables as ALPACA_KEY and ALPACA_SEC


![Alt text](https://github.com/Sahaj777/crypto_trading_bot/blob/main/Screenshot%20from%202023-07-01%2010-43-06.png "Output")

Original algorithm used here can be found on [Medium](https://medium.com/@sahajgodhani777/building-a-automate-your-crypto-trading-bot-using-alpaca-trading-in-python-a9a5fa095eea).

Made by Sahaj Godhani
Github: https://github.com/Sahaj777
