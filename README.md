# htf-macd-tradingview
A MACD indicator that can show higher timeframe MACD on a lower timeframe  

Higher Timeframe MACD [Jenny981746]

**Reason for Development**  
I need to monitor both lower timeframe and higher timeframe MACD's histogram value changes simultaneously on a lower timeframe. I found that the multiple timeframe MACD indicators developed by others tend to have delays, making it impossible to see the real-time status of MACD momentum. Therefore, I decided to develop my own indicator.

**Delay Situation of Others' Multi-Timeframe MACD Indicators**  
If I set the timeframe to 5 minutes and use both my indicator and others' indicators (set to 15 minutes), it can be observed that others' indicators will delay by one higher timeframe interval, which is 15 minutes. 
![delay of one higher timeframe interval](https://github.com/981746/htf-macd-tradingview/blob/ffee4e835fff56bbd6fb55cabdaba9c5d29e22a9/img/delay%20of%20one%20higher%20timeframe%20interval.png)

**Usage**  
Suppose we want to monitor both 5-minute MACD and 15-minute MACD on a 5-minute timeframe chart. You can first open the built-in MACD indicator in TradingView to monitor the 5-minute MACD. Then open this indicator and set the timeframe to 15 minutes. It's worth noting that there will be blue and red dots above each momentum bar; blue dots represent historical data, while red dots represent real-time data. So, the latest momentum bar will have a red dot and will change according to the real-time momentum value.
![select timeframe](https://github.com/981746/htf-macd-tradingview/blob/ffee4e835fff56bbd6fb55cabdaba9c5d29e22a9/img/select%20timeframe.png)
![monitor 5m macd and 15m macd at the same time](https://github.com/981746/htf-macd-tradingview/blob/ffee4e835fff56bbd6fb55cabdaba9c5d29e22a9/img/monitor%205m%20macd%20and%2015m%20macd%20at%20the%20same%20time.png)






