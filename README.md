📈 Stock News Alert System

Overview:
  A Python-based stock monitoring system that tracks daily stock price movements and sends SMS alerts when significant percentage changes occur. The application integrates financial market data with real-time news reporting to provide       contextual alerts.

  When a stock price moves beyond a defined threshold, the system automatically retrieves related news articles and sends formatted notifications via SMS.

Features:

📊 Daily stock price tracking using Alpha Vantage API
📈 Percentage change calculation between trading days
📰 News article retrieval via NewsAPI
🚨 Conditional alert threshold detection
📱 SMS notifications using Twilio
🔐 Secure credential handling (recommended via environment variables)
🔄 Multi-API workflow integration

How It Works:

Fetch daily stock price data.
Calculate percentage change between yesterday and the previous day.

If the change exceeds the defined threshold:

Fetch top 3 related news articles.
Format stock movement + headlines.
Send SMS alerts to the user.

Technologies Used:

Python
REST APIs
Alpha Vantage API
NewsAPI
Twilio API
Requests Library
