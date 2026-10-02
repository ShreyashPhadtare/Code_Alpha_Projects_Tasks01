# Web Scraping Using Python

## Project Overview

This project demonstrates web scraping using Python. It extracts book titles, prices, and availability from [Books to Scrape](https://books.toscrape.com/), a practice website for learning web scraping.

The project uses Requests to connect to the website, BeautifulSoup to parse HTML, and Pandas to organize and save the extracted data.

## Features

* **Website Connection:** Connects to the website using Requests.
* **Data Extraction:** Collects book titles, prices, and availability.
* **HTML Parsing:** Extracts information using BeautifulSoup.
* **Data Processing:** Organizes the data using Pandas.
* **CSV Export:** Saves the extracted information to `books_dataset.csv`.

## Technologies Used

* Python
* Requests
* BeautifulSoup
* Pandas

## Project Structure

```text
WebScraping/
├── web_scraping.py
├── books_dataset.csv
└── README.md
```

## How to Run

1. Install the required libraries:

   ```bash
   pip install requests pandas beautifulsoup4
   ```

2. Run the Python script:

   ```bash
   python web_scraping.py
   ```

3. Find the generated `books_dataset.csv` file in your project folder.

## Output

The CSV dataset contains three columns:

* Title
* Price
* Availability

The script extracts the books displayed on the first page of the website.

## Learning Outcomes

* Learned the basics of web scraping.
* Practiced HTML parsing with BeautifulSoup.
* Used Pandas to organize data.
* Exported data into CSV format.

## Task Details

**Task 1: Web Scraping**

This project was developed for Python and data analytics learning purposes.
