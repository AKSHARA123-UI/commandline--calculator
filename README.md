# News Scraper

A Python project that scrapes news headlines from websites and displays them.

## Project Description
This project allows users to fetch the latest news headlines automatically from different news websites using Python and BeautifulSoup.  
It stores the headlines along with a timestamp for easy tracking and can be extended to save data in CSV or a database.

```python
# Example usage:

from scraper import get_headlines

headlines = get_headlines("https://timesofindia.indiatimes.com/")
for headline in headlines:
    print(headline)
