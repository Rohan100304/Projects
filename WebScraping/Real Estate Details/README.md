# 🏘️ 99acres Real Estate Data Scraping Project

## 📌 Project Overview

This project involves web scraping real estate property listings from the **99acres.com** website, specifically focusing on Bengaluru properties. The collected data includes details like price, location, BHK configuration, area, furnishing status, and more. The data is then saved in a structured Excel file for further analysis.

---

## 🎯 Project Objective

To extract and structure real estate listing data from a popular property portal to:

- Analyze current property trends in Bengaluru.
- Create a dataset for housing market research.
- Provide a reference dataset for machine learning or data visualization projects.

---

## 🛠️ Tools & Technologies Used

- **Python**: Primary scripting language.
- **Libraries**:
  - `requests`: For making HTTP requests.
  - `BeautifulSoup`: For parsing HTML content.
  - `pandas`: For tabular data manipulation and exporting to Excel.
- **Jupyter Notebook**: Used for development and testing (`99acres_ScrapingData.ipynb`).

---

## 📂 Files in This Project

- `99acres_ScrapingData.ipynb` – Jupyter Notebook containing the full scraping code.
- `Reconstructed_Script.py` – A cleaned version of the scraping logic.
- `bengaluru-properties-99acres.xlsx` – Final structured dataset.
- `bengaluru-properties-99acres(Uncleaned_data).xlsx` – Raw/unprocessed data.

---

## 📈 Key Features of the Scraper

- Automatically navigates multiple pages.
- Extracts:
  - Property Name / Title
  - Price
  - Location
  - Property Type and Configuration
  - Area (in sq. ft.)
  - Furnishing Status
- Stores data in Excel format.

---

## 📌 Usage Instructions

1. Clone the repository or download the files.
2. Make sure required libraries (`requests`, `bs4`, `pandas`) are installed.
3. Run the `Reconstructed_Script.py` or the notebook in a Python environment.
4. Output Excel file will be generated with all scraped data.

---

## 💡 Use Cases of Web Scraping in Real Estate

- **Market Analysis**: Scrape data to monitor pricing and demand trends.
- **Investment Research**: Identify profitable locations.
- **Automation**: Replace manual data collection from listing platforms.

---


This project is for educational purposes only. Web scraping must always respect the target website's terms of service and robots.txt policy.
