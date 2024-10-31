# -Stock-Data-Scraper
This project is a Python-based web scraper that gathers real-time stock data from Groww.in for various U.S. stocks and one Indian stock. Using the requests library, the script sends HTTP GET requests to each specified stock URL, then parses the HTML response using BeautifulSoup to extract key financial information, such as stock price, daily price change, and trading volume. The scraped data is compiled into a structured format and saved as an Excel file.

Key Features
Web Scraping: Retrieves stock information for a list of selected stocks.
Data Extraction: Extracts company name, stock price, daily price change, and volume from each page.
Data Persistence: Saves the final data as an Excel file (stocks.xlsx) for easy access and analysis.
Error Handling: Catches attribute errors in case of any missing elements on the page.
Rate Limiting: Implements a short delay between requests to prevent rate limiting by the server.
Requirements
requests
BeautifulSoup from bs4
pandas
time
Usage
Install the required libraries using pip.
Run the script to scrape data and generate the Excel file with stock information.
