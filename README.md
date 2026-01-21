# capstone-project

A few things to note before running this project.

1. capstone_project.ipynb is only meant for testing purposes and uses historical data for faster results. So this is not live trading.
2. .env file is a must with all the details:
   GEMINI_API_KEY
   BINANCE_TEST_API_KEY = 
   BINANCE_TEST_API_SECRET =
3. The Archive.zip has 3 files that are used for actual trading, this version uses real-time data to make trades on the Binance Testnet. You can add the API Keys into the config.py file.
4. Failure Analysis and Wrong Prediction examples are extremely difficult to get with this type of bot as Gemini RateLimits in the Free Tier catch up before we get to execute any trades and the LowFrequency High Confidence Strategy here makes it so that most of the decisions that the AI makes equal to HOLD and not trade.
