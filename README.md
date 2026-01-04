# Web Scraping Projects using Python 🕷️

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-Web%20Scraping-green)
![Selenium](https://img.shields.io/badge/Selenium-Browser%20Automation-brightgreen?logo=selenium)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Status](https://img.shields.io/badge/Status-Active-success)

This repository contains a set of **Python-based web scraping projects** built using **BeautifulSoup** and **Selenium**.
The projects demonstrate how to extract structured data from both **static** and **dynamic** websites by analyzing HTML structure and automating browser actions.

---

## 🕸️ What is Web Scraping?

**Web scraping** is the process of automatically collecting data from websites by parsing their HTML content or interacting with them programmatically.

In simple terms:

* Websites show data to humans
* Web scraping extracts that same data for programs

There are two main types:

* **Static Scraping** – Data is available directly in HTML (handled using `requests` + `BeautifulSoup`)
* **Dynamic Scraping** – Data loads via JavaScript (handled using `Selenium`)

Web scraping is commonly used for:

* Data analysis
* Price monitoring
* Research and statistics
* Automation tasks
* Learning real-world data handling

⚠️ Always scrape responsibly and respect website terms of service.

---

## 📁 Projects Included

### 1️⃣ IMDB Web Scraper (BeautifulSoup)

**File:** `BeautifulSoup_IMDB.ipynb`

* Scrapes movie data from IMDB
* Extracts:

  * Movie title
  * Rating
  * Release year
* Uses **requests** + **BeautifulSoup**
* Example of **static website scraping**

---

### 2️⃣ Quotes to Scrape (Selenium)

**File:** `Selenium_QuotesToScrape.ipynb`

* Scrapes quotes from *quotes.toscrape.com*
* Handles **pagination**
* Extracts:

  * Quote text
  * Date (instead of author)
* Uses **Selenium WebDriver**
* Demonstrates automated browsing and page navigation

---

### 3️⃣ Rotten Tomatoes Scraper (Selenium)

**File:** `Selenium_RottenTomatoes.ipynb`

* Scrapes movie data from Rotten Tomatoes
* Handles **dynamic JavaScript-rendered content**
* Extracts:

  * Movie titles
  * Ratings / scores
* Uses Selenium for real-world dynamic scraping

---

## 🛠️ Tech Stack

* **Python 3**
* **BeautifulSoup (bs4)**
* **Selenium**
* **Chrome WebDriver**
* **Jupyter Notebook**

---

## ⚙️ Setup Instructions

1. Clone the repository

   ```bash
   https://github.com/ShresthGarg7/WebScraping.git
   ```

2. Install dependencies

   ```bash
   pip install beautifulsoup4 selenium requests
   ```

3. Download **ChromeDriver** (match your Chrome version)
   Add it to PATH or keep it in the project directory.

4. Run notebooks

   ```bash
   jupyter notebook
   ```

---

## 📌 Notes

* Selenium requires a browser to run.
* Website layouts can change; selectors may need updates.
* These projects are for **educational purposes only**.

---

## 🚀 Skills Demonstrated

* HTML inspection & parsing
* Static vs dynamic scraping
* Selenium automation
* Pagination handling
* Real-world data extraction

---
