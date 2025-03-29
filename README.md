# AutomateAPIpull

# Cryptocurrency Data Extraction

This project automates the extraction of cryptocurrency data from the CoinMarketCap API and stores it in a CSV file for further analysis.

## Features
- Fetches real-time cryptocurrency data from the CoinMarketCap API.
- Saves extracted data into a structured CSV file.
- Can be scheduled to run at specific intervals for continuous data collection.

## Usage
1. Get an API key from [CoinMarketCap](https://pro.coinmarketcap.com/).
2. Update the API key in the script:
   ```python
   API_KEY = "your_api_key_here"
   ```
3. Run the script:
   ```sh
   python extract_crypto_data.py
   ```
4. The extracted data will be stored in `API.csv`.

