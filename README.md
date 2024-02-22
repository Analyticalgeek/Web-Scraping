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
- libraries


         import requests
         import pandas as pd
         from bs4 import BeautifulSoup
         from tqdm import tqdm

**File**
- [book_scrape.ipynb](https://github.com/Analyticalgeek/Web-Scraping/blob/main/Books%20Scrape.ipynb): Jupyter Notebook version of the Books Scraper script for interactive usage and demonstration.
- The Informations Scraped Includes Book Title, Category, UPC ID, Price exclding taxes, Price_incl_tax, Total_Price, Ratings,	Availability, In_Stock_Books, Description, Book_link and Image_link

## 3. Dynamic Wikipedia Scraper by Title 🌐
Harnessing the power of Requests, Beautiful Soup our Dynamic Wikipedia Scraper fetches information dynamically from Wikipedia articles based on your provided titles. Expand your knowledge with ease!

**Dependencies 📦**: Ensure you have the following dependencies installed - 
- Python (3.x recommended)
- Jupyter Notebook
- libraries


         import requests
         from bs4 import BeautifulSoup
  
**File**
- [Dynamic_wikipedia_Scrape_by_title.ipynb](https://github.com/Analyticalgeek/Web-Scraping/blob/main/Dynamic%20Wikipedia%20Scrape%20by%20Title.ipynb): Jupyter Notebook version of the wikipedia Scraper script for interactive usage and demonstration.
- Given the title, this scrpit scrapes the information containing in the wikipedia page of the pariticular title.

## 4. Youtube Channel GeekForGeeks Scrape 📹
**Why ?🤔** Scraping a YouTube channel allows for in-depth analysis of video content, engagement metrics, and audience demographics. This data can be valuable for content creators, marketers, and researchers to understand trends and preferences. By scraping data from competitor channels, businesses can gain insights into their strategies, content performance, and audience engagement, enabling them to refine their own approach and stay competitive and By automating the scraping process, users can generate regular reports on channel performance, trends, and metrics, saving time and effort compared to manual data collection and analysis.

**Dependencies 📦**: Ensure you have the following dependencies installed - 
- Python (3.x recommended)
- Jupyter Notebook
- libraries


         !pip install selenium
         
         from selenium import webdriver
         from bs4 import BeautifulSoup
         import pandas as pd
         import numpy as np
         import time
         from tqdm import tqdm

  **File**
- [Youtube_GFG_Channel_Scrape.ipynb](https://github.com/Analyticalgeek/Web-Scraping/blob/main/Youtube%20Geek%20For%20Geeks%20channel%20Scrape/YouTube%20GeekforGeeks%20Scrape.ipynb): Jupyter Notebook version of the Youtube Scraper script for interactive usage and demonstration.
- [gfg_channel.csv](https://github.com/Analyticalgeek/Web-Scraping/blob/main/Youtube%20Geek%20For%20Geeks%20channel%20Scrape/gfg_videos.csv): CSV file contains the scraped Videos Title, Views, Date_time, Video_link, Thumbnail_link of both videos and live sections of channel.

## 5. Stock Image Scraper 📷
🔍 Looking for images to train an algorithm? How about using a stock image scraper? 🖼️ It's like a treasure hunt for data! 🕵️‍♂️ With this Scraping Script, you can scrape and download a vast array of images to fuel your algorithm's learning journey. 🚀 Time to dive into the sea of pixels and unlock the power of visual recognition! 🌟

**Steps Included**:
**1.** [Stock_Images_Scrape_notebook](https://github.com/Analyticalgeek/Web-Scraping/blob/main/Stock%20Image%20Scrapper/1.%20Stock%20Images%20Website%20Scrape%20-%20Infinite%20scroll.ipynb) - The Script starts with scraping this [website](https://stockmages.netlify.app) for information like image link, tags, likes and comments of the Images.

- The Scraped Information is saved in the [Stock_Images](https://github.com/Analyticalgeek/Web-Scraping/blob/main/Stock%20Image%20Scrapper/images.csv) csv file
- From the each Image link in the Stock_Images file, the script dwonloads the Images to the system.








