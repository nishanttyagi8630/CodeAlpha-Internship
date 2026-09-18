# CodeAlpha_WebScraping 📊

## Task 1: Web Scraping — CodeAlpha Data Analytics Internship

### 📌 Objective
Extract book data (title, price, rating, availability) from a live website using Python web scraping techniques.

### 🛠 Tools & Libraries Used
- Python
- BeautifulSoup4
- Requests
- Pandas

### 🌐 Data Source
[books.toscrape.com](http://books.toscrape.com) — a sandbox website built for practicing web scraping.

### 🔍 Process
1. Sent HTTP requests to fetch HTML pages (5 pages scraped).
2. Parsed HTML using BeautifulSoup to locate book elements.
3. Extracted Title, Price, Rating, and Availability for each book.
4. Cleaned and structured the data using Pandas.
5. Exported the final dataset to CSV.

### 📁 Output
`books_scraped_data.csv` — contains ~100 books with 4 columns.

### 📈 Key Learnings
- Handling HTML structure and navigating nested tags.
- Converting star-rating classes into numeric ratings.
- Respecting website load with request delays (`time.sleep`).
- Structuring scraped data into a clean, analysis-ready format.

### 🔗 About CodeAlpha
This project is part of the Data Analytics Internship at CodeAlpha.

---
📩 Feel free to connect and share feedback!
