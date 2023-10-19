# QotesSpider - A Scrapy Spider for Scraping Quotes

## Description
QotesSpider is a Python web scraping spider created using Scrapy. It is designed to scrape quotes from the website 'https://quotes.toscrape.com/' and save the extracted data in an output.json file.

## Spider Functionality:
The QotesSpider works as follows:

1. It starts by sending a request to the 'https://quotes.toscrape.com/' URL.
2. The spider locates all quote elements on the page using CSS selectors.
3. For each quote element, it extracts the title, author, and tags.
4. The extracted data is yielded as a dictionary and saved in the output.json file.

### Output
The spider will create an output.json file in the project directory, containing the scraped data in JSON format.



