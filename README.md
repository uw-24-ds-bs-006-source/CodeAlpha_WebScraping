# CodeAlpha_WebScraping

## 📌 Project Overview
This project is **Task 1 (Web Scraping)** for the **CodeAlpha Data Analytics Internship**.  
It uses Python (`requests` and `BeautifulSoup`) to scrape book catalog data from [Books to Scrape](https://books.toscrape.com/) across the first 5 pages (**100 books** total) and exports the cleaned, structured dataset to `books_dataset.csv` using `pandas`.

---

## 🛠️ Tools & Libraries Used
- **Python 3** (Google Colab)
- **requests** — Fetching webpage HTML with UTF-8 encoding
- **BeautifulSoup (`bs4`)** — Parsing HTML tags and extracting elements via CSS selectors
- **pandas** — Structuring extracted records into a DataFrame and exporting to CSV

---

## 📊 Dataset Description (`books_dataset.csv`)
The scraped dataset contains **100 rows** and **5 columns**:

| Column | Description |
| :--- | :--- |
| `title` | Sapiens: A Brief History of Humankind |
| `price` | Display price in GBP (`£`) |
| `price_gbp` | Cleaned numeric price (`float`) ready for analysis |
| `rating` | Star rating (`One` to `Five`) |
| `availability` | Stock status (`In stock`) |

---

## 🚀 How to Run
1. Install the required libraries:
   ```bash
   pip install requests beautifulsoup4 pandas
