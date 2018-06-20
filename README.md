# Binance Trader (RC 2)

This is a Binance trading bot. The implementation of the web interface was forked from https://github.com/yasinkuyu/binance-trader. The model is a Many-To-One RNN, that attemps to map historical prices over the past hour in 5 minute intervals to a new price that should occur in 15 minutes.


Detailed reports of the performance of the bot, and my earnings, should be found on my Medium (@jparthasarthy) in the coming weeks as I compile a detailed write-up. 

# Usage

Follow the set-up instructions at https://github.com/yasinkuyu/binance-trader. Launch the bot in Network Mode. The bot updates its predictions every 5 minutes, but will only buy if confidence > 0.8. You can change this by modifying the source code in the trading file. 
