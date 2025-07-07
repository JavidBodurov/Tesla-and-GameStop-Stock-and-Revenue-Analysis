
# 📊 Tesla and GameStop Stock & Revenue Analysis

This Jupyter Notebook project demonstrates how to extract, clean, and visualize stock and revenue data for **Tesla (TSLA)** and **GameStop (GME)** using Python. It integrates real-time stock data from Yahoo Finance and quarterly revenue data extracted via web scraping.

---

## 🧠 Project Objectives

- ✅ Extract historical stock data using `yfinance`.
- ✅ Scrape quarterly revenue data using `requests` and `BeautifulSoup`.
- ✅ Clean and preprocess the data with `pandas`.
- ✅ Create dual-axis plots comparing stock prices vs. revenue over time.

---

## 📁 Files Included

- `Tesla_and_GME_date_revenue.ipynb`: Jupyter notebook containing the full code and visualizations.
- `README.md`: This project description file.

---

## 📦 Installation

Before running the notebook, install the required libraries:

```bash
pip install yfinance
pip install pandas
pip install matplotlib
pip install beautifulsoup4
pip install lxml
```

---

## 🚀 Usage Instructions

1. Clone or download this repository.
2. Open the notebook `Tesla_and_GME_date_revenue.ipynb` in Jupyter or VS Code.
3. Run each cell in sequence to:
   - Load Tesla and GameStop stock data
   - Web scrape revenue data
   - Clean and preprocess datasets
   - Plot stock prices and revenue data

---

## 🧾 Data Sources

- **Stock Data**: Fetched using [`yfinance`](https://pypi.org/project/yfinance/) from Yahoo Finance.
- **Revenue Data**: Scraped from [Macrotrends.net](https://www.macrotrends.net/).

---

## 📊 Output Visualizations

The notebook includes dual-axis line plots for:
- **Tesla**: Stock price vs. revenue
- **GameStop**: Stock price vs. revenue

Each graph helps visualize how financial performance correlates with market valuation.

---

## 🤝 Acknowledgements

- IBM Data Science Capstone Project on Coursera
- Yahoo Finance API via yfinance
- Macrotrends for financial data

---

## 🧑‍💻 Author

Javid Bodurov – Data Analyst & Aspiring Data Scientist

---

## 📜 License

This project is for educational purposes only. Commercial use of scraped data is subject to the original data provider’s terms.
