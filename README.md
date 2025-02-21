# IB
This is use for building trading bot

Bot
1. grid bot
2. martinangle bot
3. Statistical arbitrage
	3.1 Calculate the spread between two asset
		- P<sub>a<\sub> = \alpha + \beta P<sub>b<\sub> + e
	3.2 Perform ADF test for the stability of the spread
		- If reject, proven the spread is stationary
		- High chance for the spread to turn back to 0
	3.3 Set Reverse parameter
		- e.g. 1.5 SD of the spread away from mean
	3.4 Backtest