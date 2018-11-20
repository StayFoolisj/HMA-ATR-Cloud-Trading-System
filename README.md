# HMA-ATR-Cloud-Trading-System
Algorithmic trading system based on HMA's and ATR written in Pinescript, a scripting language 
native to the trading platform Tradingview.com

Basically just playing around with some ideas. Hull MA's have good entries and exits on their own, but together with ATR I find them to be even more solid. Only tested with crypto. Best results on daily timeframe and long only. 

Stop loss, trailing and pyramiding code is functional. There is also a long only / short only option in the bottom of the settings. 

Let me know what you think

![backtesting](https://image.ibb.co/jyzmfL/Screen-Shot-2018-11-20-at-12-27-33.png)

# How to add
1. Copy the script and go to tradingview.com and open any chart
2. On the bottom of your screen you'll see [Pine Editor]. Click this and paste the script here. Then click [Add to Chart]
3. You should now see the indicator added to you chart
4. You can edit its settings by clicking the cog wheel icon right next to its name

# How to use
Based on the settings, it will generate entry and exit signals on its own. If you have a tradingview account you can setup alarms based on its signals. 

Based on the settings you use, it will generate entry and exit signal for both long and short positions. There is also 
functional risk management mechanisms in the code. You can find it in your settings. 

FYI signals are signalled 'after the fact', which means the next bar. This is a pinescript limitiation which is very tricky to overcome without generating false signals. 

