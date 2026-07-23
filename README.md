# BeautifulSoup Web Scraping Project

## Overview
A web scraping project using Python, BeautifulSoup 
and Pandas to scrape 1,000 books from the Books to 
Scrape website. This project demonstrates the ability 
to extract, clean and analyze data directly from 
websites without manual copying.

## Tools Used
- Python
- BeautifulSoup4
- Requests
- Pandas
- Matplotlib
- JupyterLab

## What This Project Does
- Sends HTTP requests to a website using Requests
- Parses HTML content using BeautifulSoup
- Extracts book titles, prices, ratings and availability
- Scrapes all 50 pages automatically
- Cleans and structures the data using Pandas
- Analyzes and visualizes the findings

## Key Findings
- Successfully scraped 1,000 books across 50 pages
- Average book price is £35.07
- Most expensive book costs £59.99
- Cheapest book costs £10.00
- One star rated books are most common with 226 books
- Price does not significantly vary by rating — 
  average price is similar across all rating levels
- All 1,000 books are In Stock

## Skills Demonstrated
- Web scraping with BeautifulSoup and Requests
- HTML parsing and CSS selector usage
- Multi-page scraping automation
- Data cleaning with Pandas
- Data visualization with Matplotlib
- Handling real world unstructured web data

## How To i Ran This Project
1. Install required libraries:
2. Open `beautifulsoup_tutorial.ipynb` in JupyterLab
3. Run all cells from top to bottom
4. The scraper will automatically collect all 1,000 books

## Dataset
The scraped data is saved in `books_scraped.csv` 
containing 1,000 rows and 6 columns:
- Title
- Price
- Rating
- Availability
- Page
- Rating_Num

## Website Used
Books to Scrape — a free sandbox website designed 
for web scraping practice:
bookscrape.com
