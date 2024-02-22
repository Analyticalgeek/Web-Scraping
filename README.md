# Web Scraping Toolbox 🕵️‍♂️

Welcome to the Web Scraping Toolbox! Here, you'll find a collection of handy scripts powered by Requests, Beautiful Soup, Selenium, and Pandas libraries. Let's dive into the world of web scraping and unlock the treasure trove of data on the web! 🌐💻 What's Inside?

## 1. Quotes Scraper 📚
This script utilizes Requests and Beautiful Soup to extract quotes from a [webpage](https://quotes.toscrape.com). 

**Dependencies 📦**: Ensure you have the following dependencies installed -
- Python (3.x recommended)
- Jupyter Notebook
- libraries


         import requests
         import pandas as pd
         from bs4 import BeautifulSoup
         from tqdm import tqdm

**Files**
- [quotes_scrape.ipynb](https://github.com/Analyticalgeek/Web-Scraping/blob/main/Quotes%20Scrape.ipynb): Jupyter Notebook version of the Quotes Scraper script for interactive usage and demonstration.
- [scraped_quotes.csv](https://github.com/Analyticalgeek/Web-Scraping/blob/main/Quotes.csv): CSV file containing the scraped quotes, authors, author IDs, tags, and author links.

## 2. Book Scraper 📖
This script utilizes Requests and Beautiful Soup to extract Books Information from a [webpage](https://books.toscrape.com).

**Dependencies 📦**: Ensure you have the following dependencies installed - 
- Python (3.x recommended)
- Jupyter Notebook
-libraries:

         import requests
         import pandas as pd
         from bs4 import BeautifulSoup
         from tqdm import tqdm

**File**
- [book_scrape.ipynb](https://github.com/Analyticalgeek/Web-Scraping/blob/main/Books%20Scrape.ipynb): Jupyter Notebook version of the Books Scraper script for interactive usage and demonstration.
- The Informations Scraped Includes Book Title, Category, UPC ID, Price exclding taxes, Price_incl_tax,	Total_Price,	Ratings,	Availability,	In_Stock_Books,	Description,	Book_link and Image_link

## 3. Dynamic Wikipedia Scraper by Title 🌐
Harnessing the power of Requests, Beautiful Soup our Dynamic Wikipedia Scraper fetches information dynamically from Wikipedia articles based on your provided titles. Expand your knowledge with ease!

**Dependencies 📦**: Ensure you have the following dependencies installed:
- Python (3.x recommended)
- Requests library
- Beautiful Soup library

**File**
- [Dynamic_wikipedia_Scrape_by_title.ipynb](https://github.com/Analyticalgeek/Web-Scraping/blob/main/Dynamic%20Wikipedia%20Scrape%20by%20Title.ipynb): Jupyter Notebook version of the wikipedia Scraper script for interactive usage and demonstration.
- Given the title, this scrpit scrapes the information containing in the wikipedia page of the pariticular title.

## 4. Youtube Channel GeekForGeeks Scrape 📹
**Why ?🤔** Scraping a YouTube channel allows for in-depth analysis of video content, engagement metrics, and audience demographics. This data can be valuable for content creators, marketers, and researchers to understand trends and preferences. By scraping data from competitor channels, businesses can gain insights into their strategies, content performance, and audience engagement, enabling them to refine their own approach and stay competitive and By automating the scraping process, users can generate regular reports on channel performance, trends, and metrics, saving time and effort compared to manual data collection and analysis.

**Dependencies 📦**: Ensure you have the following dependencies installed:
         !pip install selenium

         from selenium import webdriver
         from bs4 import BeautifulSoup
         import pandas as pd
         import numpy as np
         import time
         from tqdm import tqdm

- Python (3.x recommended)
- Requests library
- Beautiful Soup library
- Pandas library
- numpy library
- tqdm library (optional for progress tracking)






 
  
  
