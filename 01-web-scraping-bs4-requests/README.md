# 🌐 Web Scraping with Requests, BeautifulSoup4 & Scaffolding

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Library](https://img.shields.io/badge/Library-BeautifulSoup4-teal.svg)](https://www.crummy.com/software/BeautifulSoup/)
[![Topic](https://img.shields.io/badge/Topic-Web%20Scraping-lightgrey.svg)](#)

## 📌 Project Overview
This module demonstrates automated data extraction from web sources. It covers HTTP request management, User-Agent header spoofing to prevent automated bot blocks, HTML DOM parsing, tag extraction, and starter templates for large-scale crawling frameworks.

---

## 📚 Components Included
1. **Interactive Notebook ([`web_scraping_bs4_requests.ipynb`](./web_scraping_bs4_requests.ipynb))**:
   - HTTP GET requests with `requests`.
   - Custom `User-Agent` headers to simulate desktop and mobile browsers.
   - HTML parsing with `BeautifulSoup` and `html5lib`.
   - Node extraction (`find`, `find_all` for `h1`..`h6` headers).
   - DOM cleaning with `.decompose()` for `script` and `style` elements.
2. **Framework Scaffolding ([`web_scraping_template.py`](./web_scraping_template.py))**:
   - Python template importing Scrapy, BeautifulSoup, Selenium, and Pandas for enterprise crawling pipelines.

---

## 💻 Code Structure
- **Notebook**: [`web_scraping_bs4_requests.ipynb`](./web_scraping_bs4_requests.ipynb) (6 cells)
- **Script**: [`web_scraping_template.py`](./web_scraping_template.py) (import scaffold)
- **Dependencies**: `requests`, `beautifulsoup4`, `html5lib`, `scrapy`, `selenium`, `pandas`

---

## 🚀 How to Run
```bash
pip install requests beautifulsoup4 html5lib scrapy selenium pandas
jupyter notebook web_scraping_bs4_requests.ipynb
```
