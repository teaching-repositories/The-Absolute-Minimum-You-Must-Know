# Web Scraping in Python: The Absolute Minimum You Must Know

Web scraping extracts data from websites using Python.

## Requests 

Import Requests to download web pages:

```python
import requests
```

## Get a Web Page

Use `requests.get()` to download a page:

```python
response = requests.get('https://example.com')
```

## Parse HTML

Use Beautiful Soup to parse HTML:

```python
from bs4 import BeautifulSoup

soup = BeautifulSoup(response.text)
```

## Find Elements

Target elements by CSS selectors:

```python 
titles = soup.select('h1')
```

## Extract Data

Extract text, attributes, etc:

```python
text = titles[0].text
link = soup.select_one('a')['href']
```

## Store Data

Save scraped data to a file or database.

That covers the basics of web scraping with Python! You can now extract data from websites into structured data.