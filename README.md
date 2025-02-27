# Cryptocurrency Market Data Fetcher

This Python script fetches the latest cryptocurrency market data from the CoinGecko API, processes it, and saves the top gainers, top losers, and the full market data into CSV files.

## Features

- Fetches cryptocurrency market data from the CoinGecko API.
- Identifies the top 10 gainers and top 10 losers based on the 24-hour price change percentage.
- Saves the data into CSV files with a timestamp for easy tracking.
- Displays the top gainers and losers in the console.

## Prerequisites

Before running the script, ensure you have the following installed:

- Python 3.x
- `requests` library
- `pandas` library
