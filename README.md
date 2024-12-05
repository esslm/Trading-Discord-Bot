# 🤖 Crypto Trading Discord Bot

A powerful Discord bot that provides real-time cryptocurrency information and AI-powered trading analysis using Binance's public API.

## ✨ Features

- 📊 Real-time cryptocurrency price information
- 🧠 AI-powered trading analysis
- 📈 Technical indicators (RSI, EMA, Bollinger Bands)
- 💹 Market trend analysis
- 📉 Support and resistance levels
- ⚡ Fast and reliable (powered by Binance API)
- 🔒 No API keys required for price data

## 🚀 Commands

- `!price <symbol>` - Get current price and 24h statistics
  ```
  Example: !price BTC
  ```
  Shows current price, 24h change, high/low prices, volume, and number of trades

- `!analyze <symbol>` - Get detailed market analysis
  ```
  Example: !analyze ETH
  ```
  Provides comprehensive analysis including:
  - Market trend
  - Trading signals
  - Support/Resistance levels
  - RSI indicator
  - Volume analysis
  - Risk assessment
  - Trading recommendations

## 📋 Prerequisites

- Node.js v16.9.0 or higher
- Discord.js v14
- A Discord Bot Token

## ⚙️ Installation

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/crypto-trading-bot.git
   cd crypto-trading-bot
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Create a .env file in the root directory
   ```env
   DISCORD_TOKEN=YOUR_DISCORD_BOT_TOKEN
   ```

4. Start the bot
   ```bash
   node .
   ```

## 🛠️ Technology Stack

- Discord.js
- Node.js
- Axios for API requests
- Technical Indicators library
- Binance public API

## 📊 Technical Analysis Features

- RSI (Relative Strength Index)
- EMA (Exponential Moving Average)
- Bollinger Bands
- Volume Analysis
- Support/Resistance Detection
- Trend Analysis
- Risk Assessment

## ⚠️ Disclaimer

This bot is for informational purposes only. The trading signals and analysis provided should not be considered as financial advice. Always do your own research and trade at your own risk.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/yourusername/crypto-trading-bot/issues).

## 🌟 Show your support

Give a ⭐️ if this project helped you!
