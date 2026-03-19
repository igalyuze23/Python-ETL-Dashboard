# 📊 Python ETL Pipeline & Excel Dashboard

## 📌 Project Overview
This project is a foundational **ETL (Extract, Transform, Load)** pipeline built entirely with Core Python. It is designed to automatically process raw data and generate an organized, ready-to-use Excel dashboard for business reporting.

The script extracts unstructured data from **JSON** files, applies data cleaning and business logic using native Python data structures, and exports the final metrics into a formatted Excel spreadsheet.

## 🛠️ Technical Highlights
* **Data Extraction:** Reading and parsing nested data from `JSON` files.
* **Data Transformation:** Using Core Python (Loops, Lists, and Dictionaries) to clean, aggregate, and structure the data efficiently without relying on heavy external data libraries.
* **Automated Reporting (Load):** Utilizing the `openpyxl` library to dynamically generate a multi-sheet Excel report, turning raw numbers into an accessible dashboard.

## 💻 Tech Stack
* **Language:** Python 3
* **Libraries:** `json` (Data Parsing), `openpyxl` (Excel Automation)
* **Core Skills Demonstrated:** Data Structures (Dicts/Lists), File I/O, Automation, ETL Logic.

## 🚀 How It Works
1. The script reads the raw data from the local JSON files.
2. It processes and aggregates the metrics based on predefined business rules.
3. An automated Excel file is generated containing the cleaned data and summarized dashboard metrics.
