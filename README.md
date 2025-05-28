# 📚 Quotes Web Scraper using Selenium

This project demonstrates how to use **Selenium** to scrape data from a website. Specifically, it collects quotes, authors, and associated tags from [http://quotes.toscrape.com](http://quotes.toscrape.com) and stores the data in a CSV file.

---

## 🧠 What is Selenium?

**Selenium** is an open-source automation tool used for web applications. It can be used to automate browsers, test applications, and extract (scrape) data from dynamic or static websites.

Selenium is especially useful when:
- The website is JavaScript-heavy.
- Traditional tools like `requests` or `BeautifulSoup` don’t work properly due to dynamic content loading.

---

## 🛠️ Setup Instructions

### 1. Install Python
Ensure you have Python 3.7 or above installed on your machine.

### 2. Install Required Packages
You’ll need:
- `selenium`

To install it, run:

`pip install selenium`

   
### 3. Download ChromeDriver
Since we are using the **Chrome browser**, download the corresponding version of **ChromeDriver**:

- Visit: [https://sites.google.com/chromium.org/driver](https://sites.google.com/chromium.org/driver)
- Download the driver that matches your **Chrome browser version**.
- Extract it and note the path to `chromedriver.exe`.

### 4. Add Chromedriver Path
Update the path to `chromedriver.exe` in the script accordingly.

---

## 🔍 How It Works

1. The script launches Chrome using Selenium.
2. It opens the quote website.
3. It loops through the first 3 pages and extracts:
   - Quote text
   - Author name
   - Associated tags
4. The data is stored in a list of dictionaries.
5. Finally, the data is exported to a CSV file for easy use.

---

## 📁 Output

After successful execution, the script will create a file:
- `quotes_data.csv` — containing the extracted quote data.

---

## 📌 Notes

- The website used is specifically designed for practicing web scraping.
- Make sure to always respect a website’s `robots.txt` and **terms of service** when scraping real-world sites.

---

## ✅ Requirements Summary

- Python 3.7+
- Selenium
- Chrome browser
- ChromeDriver (matching your Chrome version)

---

## 💡 Author

Created for educational purposes to demonstrate basic to intermediate-level web scraping using Selenium.

