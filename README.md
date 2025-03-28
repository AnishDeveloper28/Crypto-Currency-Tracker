# Crypto Currency Tracker

A real-time cryptocurrency tracking application that displays market data for top cryptocurrencies.

🔗 **Live Demo:** [Crypto Currency Tracker](cryptotrakz.netlify.app)

Crypto Currency Tracker
A real-time cryptocurrency tracking web application that displays market data for top cryptocurrencies using the CoinGecko API.

🔗 Live Demo: Crypto Currency Tracker

📌 Features
✅ Real-time cryptocurrency data from CoinGecko API
✅ Search functionality to filter by cryptocurrency name or symbol
✅ Sorting options for:

Market Cap (highest to lowest)

24-hour Percentage Change (highest to lowest)
✅ Key metrics displayed:

Current Price

24h Price Change

Market Cap

Trading Volume
✅ Visual indicators for price changes (green for up, red for down)
✅ Cryptocurrency icons for better visualization
✅ Fully responsive design

🛠 Tech Stack
Frontend: HTML5, CSS3, JavaScript (Vanilla)

API: CoinGecko API

🔗 API Integration
The application fetches real-time data from the CoinGecko API v3:

bash
Copy
Edit
https://api.coingecko.com/api/v3/coins/markets?vs_currency=usd&order=market_cap_desc&per_page=10&page=1&sparkline=false
📊 Data Includes:
✔ Top 10 cryptocurrencies by market cap
✔ USD currency pairing
✔ 24-hour price change data

⚡ Key Features & Functionality
📡 Data Fetching
Uses fetch() to retrieve live market data

Handles API errors and rate limits gracefully

🔎 Search Functionality
Case-insensitive search

Filters results in real-time based on cryptocurrency name or symbol

📊 Sorting Options
Sorts by Market Cap (highest to lowest)

Sorts by 24h Price Change (highest to lowest)
