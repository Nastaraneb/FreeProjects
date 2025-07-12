# 📈 Stock Data Analysis and Revenue Comparison Project

This project combines **web scraping**, **data analysis**, and **visualization** to examine and compare the historical stock prices and reported revenues of three major tech companies: **Apple (AAPL), Microsoft (MSFT), and Alphabet/Google (GOOGL)**.

## 🚀 Project Overview

- 🔄 Scraped and cleaned revenue data from the web
- 📊 Retrieved historical stock data using the `yfinance` Python library
- 🧹 Cleaned and merged datasets
- 📉 Visualized trends in stock prices and revenues

## 📦 Technologies Used

- `Python`
- `Pandas`
- `yfinance`
- `BeautifulSoup`
- `matplotlib`
- `requests`

## 🧾 Steps

### 1. Data Collection
- Fetched historical stock price data from **Yahoo Finance** using `yfinance`.
- Web scraped quarterly revenue data from **Macrotrends.net** using `requests` and `BeautifulSoup`.

### 2. Data Cleaning & Processing
- Removed commas and dollar signs from revenue columns
- Converted string dates to proper datetime formats
- Filtered out rows with missing data
- Merged stock data and revenue data on `Date`

### 3. Data Visualization
- Created dual-axis line charts to compare stock price (left Y-axis) with revenue (right Y-axis)
- Plotted data for Apple, Microsoft, and Google separately

## 📌 Key Skills Demonstrated

- Web scraping real-time data using `requests` and `BeautifulSoup`
- Working with time series data
- Cleaning and transforming financial data
- Plotting with dual axes using `matplotlib`
- Saving and managing datasets in `.csv` format
- Writing modular and clean Python code in a Jupyter Notebook

## Result and Analysis 

The graphs show how the ending prices of Apple, Google, and Microsoft's stocks relate to their past sales.
All three companies have long-term income growth, which is usually shown by stock prices going up. 
However, short-term differences between price and income show that trader mood and factors in other markets can have an effect.
Strong correlation between market value and financial success shows how useful income analysis is for evaluating investments.

## 🙋‍♀️ Author

Nastaran

