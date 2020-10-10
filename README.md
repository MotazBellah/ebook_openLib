# Book API / Quotes API

Build a scrapy project which will generate two spider one to scrape openlibrary.org API to get ebooks, and another to scrape quotes.toscrape.com API to get quoutes
- https://openlibrary.org/subjects/picture_books.json
- http://quotes.toscrape.com/api/quotes

## Code style

- This project is written in python 3.
- Use Scrapy.

## Clone/Run app
````
# Clone repo
$ git clone https://github.com/MotazBellah/ebook_openLib

# Install all dependencies
$ pip install -r requirements.txt

# Run
$ cd demo_api
# Run ebooks spider to get all books
$ scrapy crawl ebooks
# Run quotes spider to get all quotes
$ scrapy crawl quotes

````
