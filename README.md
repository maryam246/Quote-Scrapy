# QotesSpider - A Scrapy Spider for Scraping Quotes

## Description
QotesSpider is a Python web scraping spider created using Scrapy. It is designed to scrape quotes from the website 'https://quotes.toscrape.com/' and save the extracted data in an output.json file.

__Spider Functionality:__
The QotesSpider works as follows:

1. It starts by sending a request to the 'https://quotes.toscrape.com/' URL.
2. The spider locates all quote elements on the page using CSS selectors.
3. For each quote element, it extracts the title, author, and tags.
4. The extracted data is yielded as a dictionary and saved in the output.json file.

### Output
The spider will create an output.json file in the project directory, containing the scraped data in JSON format.

### Sample output in output.json:

json

Copy code

[

    {
      "title": "“The world as we have created it is a process of our thinking. It cannot be changed without changing our thinking.”",
      "author": "Albert Einstein",
      "tag": "change, deep-thoughts, thinking, world"
    },

   {
      "title": "“It is our choices, Harry, that show what we truly are, far more than our abilities.”",
      "author": "J.K. Rowling",
      "tag": "abilities, choices"
   },
   ...
]

