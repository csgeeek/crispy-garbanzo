# crispy-garbanzo

This is a simple web scraper that will scrape jobs from coursera job board.

## Installation

```bash
virtualenv env
env\Scripts\activate
pip install -r requirements.txt
```


## Usage

```bash
cd scrape_era
env\Scripts\activate
scrapy crawl coursera -o jobs.csv
```
Open jobs.csv file to see the scraped data.