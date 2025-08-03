# Yahoo Stock Data Scraper

## 📌 Project Overview
This project is a stock data scraping tool that collects historical stock prices and related information from Yahoo Finance using web scraping techniques. It includes a Jupyter Notebook and a standalone executable (`.exe`) script to make it easy to use for both developers and non-technical users.

## 📁 Project Structure
```
Yahoo_stock_data/
├── Executable_Script.exe
├── Executable_Script.py
├── Stock_scraping_script.ipynb

```

## 🚀 Features
- Scrapes live stock data for any company listed on Yahoo Finance.
- Allows users to customize stock symbols, date ranges, and frequency.
- Saves the collected data in a structured format like CSV or Excel.
- Includes a compiled `.exe` file for easy usage without Python installation.

## 🛠️ Technologies Used
- Python
- Jupyter Notebook
- `requests`, `pandas`, `beautifulsoup4`
- PyInstaller (to create the `.exe` file)

## 🧠 How It Works
1. The script sends HTTP requests to Yahoo Finance.
2. It parses the HTML or JSON response to extract stock data.
3. It stores the data in a structured format.
4. The `.exe` file can be run directly to automate this process.

## 💡 Use Cases
- Financial data analysis for students or researchers.
- Personal investment tracking.
- Data collection for machine learning projects related to finance.

## 📦 How to Use
### Using Python Script
1. Run `Executable_Script.py` in Python environment.
2. Modify script to use desired ticker symbols and date ranges.

### Using the `.exe` File
1. Double-click `Executable_Script.exe`.
2. Follow the prompts to enter stock symbol and other details.

## ✅ Requirements (if running Python script)
```
pip install pandas requests beautifulsoup4
```
