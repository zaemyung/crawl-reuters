# Crawl-Reuters

A simple Scrapy script for crawling Reuters news articles (Python 3)

## Usage

1. Install Scrapy: `pip install Scrapy`
2. Modify the code in `./crawler/crawler/spiders/reuters_spider.py` to suit your needs
3. Run the script: `scrapy crawl reuters`

For more detailed information on running Scrapy scripts, visit: [Scrapy Tutorial](https://doc.scrapy.org/en/latest/intro/tutorial.html)

## Output Examples

The crawled articles for each day are saved as a JSON file at `./crawler/crawled/*year*/*month*/*date*.json`

### JSON Format Example
~~~~
{"text": ["This is the first sentence of the article.", "The second sentence is here"], "section": "Politics", "title": "Reuters News Articles Crawled", "date": "20161113"}
~~~~