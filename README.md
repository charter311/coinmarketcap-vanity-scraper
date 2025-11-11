> [!TIP] 
> # How to run
> 
> ## Install Python
> 
> 1. Go to the official Python website: https://www.python.org/downloads/release/python-3139/
> 2. Scroll down to the files part. Then download the Windows installer (64-bit)
> 3. Once downloaded, run the installer.
> 4. ✅ Important: On the first screen of the installer, check the box that says
> “Add Python to PATH” before clicking Install Now.
> ## How to download the repo
> Click the button below to download the code as a .zip:
>
> <a href="https://github.com/charter311/coinmarketcap-vanity-scraper/archive/refs/heads/main.zip"><img src="https://img.shields.io/badge/⬇️_Download_ZIP-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="Download ZIP"></a>
>
> 
> Now extract the .zip folder
> 
> ## Run the script
> 
> Open the command prompt inside the extracted folder and run:
>
> `py scraper.py`
> 
>  or
> 
> `python scraper.py`


# CoinMarketCap Vanity Scraper

## Overview
The CoinMarketCap Vanity Scraper is a Python project designed to scrape Discord and Telegram links associated with cryptocurrencies listed on CoinMarketCap. As cryptocurrency communities continue to expand across various social media platforms, this tool provides a convenient means to collect and analyze relevant social media links.

## How It Works
The CoinMarketCap Vanity Scraper interacts with the CoinMarketCap API to retrieve data on cryptocurrencies. It utilizes the API's endpoints to fetch information such as cryptocurrency listings, including their Discord and Telegram links. The scraper makes HTTP requests to the API endpoints, receives JSON responses, and parses the relevant data, specifically targeting Discord and Telegram links associated with each cryptocurrency. Once the links are extracted, they are stored in a structured format for further analysis or processing. This approach offers a more efficient and reliable method compared to web scraping, ensuring accurate and up-to-date information retrieval.


## Features
- **Scrape Discord Links:** Extract Discord server invitation links associated with cryptocurrencies.
- **Scrape Telegram Links:** Gather Telegram group links related to cryptocurrencies.
- **Customizable:** Easily adapt the scraper to handle changes in the CoinMarketCap website structure or add additional features as needed.

## Usage
1. Install dependencies:
```
pip install -r requirements.txt
```
2. Run the scraper:
```
python scraper.py
```
3. View the extracted links in the output file or integrate the scraper into your own projects for further analysis.

## Contributions
Contributions are welcome! If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.

kb