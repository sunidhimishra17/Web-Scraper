# Web-Scraper

An advanced Python-based Web Scraper and SEO Auditing tool built using BeautifulSoup and Selenium to automate data collection, inspect broken links, and measure page performance.

## Advanced Web Scraper & Website Auditor

A powerful, automation-driven web scraping and SEO auditing tool developed in Python. Unlike basic scrapers that only read static HTML, this project combines the speed of BeautifulSoup with the browser-automation capabilities of Selenium. It takes any website URL as input and generates a comprehensive technical audit of that webpage.

## Key Features

* **Dynamic Scraping:** Successfully handles JavaScript-rendered pages using Selenium.
  
* **SEO Data Extraction:** Automatically extracts Meta Descriptions, Page Titles, and core HTML structural tags (`h1` to `h6`).
  
* **Image Accessibility Audit:** Scans and extracts image `ALT` tags to verify SEO compliance.

* **Link Health Inspector:** Automatically tests links inside the webpage to detect broken links (`404 errors`).

* **Performance Tracker:** Measures both frontend and backend page loading performance.

* **Content Analysis:** Includes a built-in word counter for content length analysis.

* **Clean Data Collection:** Extracts all unique URLs from a website while automatically eliminating duplication.

* **Source Code Downloader:** Fetches and extracts raw HTML source code directly within the environment (Google Colab compatible).

## Tech Stack & Libraries Used

* **Language:** Python 3.x

* **Libraries:**

  * `BeautifulSoup4` (For HTML parsing and data extraction)

  * `Selenium` (For dynamic page rendering and interaction)

  * `Requests` (For HTTP status checks and link inspection)

  * `Time` & `Urllib` (For performance tracking and URL parsing)

## Getting Started / Installation

### Prerequisites

Make sure you have Python installed, along with a web driver (like ChromeDriver) if running Selenium locally.

### 1. Clone the Repository

    git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git]
    
    cd YOUR_REPOSITORY_NAME

### 2. Install Required Packages

    pip install beautifulsoup4 selenium requests

## How To Use

1. Open the Jupyter Notebook Web_Scraping_using_python_and_beautifulsoup.ipynb in Google Colab or your local environment.

2. Run the cells in sequence.

3. When prompted, input the target website URL.

4. The tool will process the page and output:

** Extracted text, headers, and meta data.

** A report on broken links.

** Performance metrics in seconds.

** A clean list of all unique internal/external URLs.
