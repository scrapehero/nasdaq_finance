# Nasdaq Finance Scraper
This script will scrape Nasdaq.com to extract stock market data based on a ticker symbol of a company. If you would like to know more about
this scraper you can check it out at this link https://www.scrapehero.com/scrape-nasdaq-stock-market-data/

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Fields 

This nasdaq scraper can extract the fields below

1. Best Bid/Ask
2. 1 Year Target
3. Share Volume
4. 50 Day Avg. Daily Volume
5. Previous Close
6. 52 Week High/Low
7. Market Cap
8. P/E Ratio
9.Forward P/E (1y)
10. Earnings Per Share (EPS)
11. Annualized Dividend
12. Ex-Dividend Date
13. Dividend Payment Date
14. Current Yield
15. Beta
16. Open Price
17. Open Date
18. Close Price
19. Close Date

### Prerequisites

For this web scraping tutorial using Python 3, we will need some packages for downloading and parsing the HTML. 
Below are the package requirements:

 - lxml
 - requests

### Installation

PIP to install the following packages in Python (https://pip.pypa.io/en/stable/installing/) 

Python Requests, to make requests and download the HTML content of the pages (http://docs.python-requests.org/en/master/user/install/)

Python LXML, for parsing the HTML Tree Structure using Xpaths (Learn how to install that here – http://lxml.de/installation.html)

## Running the scraper
We would execute the code with the script name followed by the ticker symbol of the company’s stock data you would like. As an example
here is the command to find the summary data for Apple Inc. 

```
python3 masdaq_finance.py aapl
```
## Sample Output

This will create a json file:

[Sample Output](https://raw.githubusercontent.com/scrapehero/nasdaq_finance/master/AAPL-summary.json)
 
 
