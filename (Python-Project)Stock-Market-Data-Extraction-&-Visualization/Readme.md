# 📊 Stock Market Data Extraction & Visualization using Python

This project is part of the IBM Data Analyst Professional Certificate and was completed after finishing the Python course module. It simulates the role of a Data Analyst at a hedge fund, with the goal of gathering, analyzing, and visualizing stock and revenue data from various sources.

The project is divided into three parts:

- **Part 1**: Web scraping historical stock data using `requests` and `BeautifulSoup`
- **Part 2**: Extracting structured stock data using the `yfinance` Python library
- **Part 3**: Analyzing and visualizing stock prices and revenues for companies like Tesla and GameStop

---

## 🧰 Tools & Libraries

- Python (Jupyter Notebook)
- `pandas`
- `requests`
- `BeautifulSoup`
- `yfinance`
- `matplotlib`

---

## 📁 Project Structure

### 🔹 Part 1: Extracting Stock Data using Web Scraping

In this section, we extract historical stock data from web pages where APIs are not available.

**Tasks:**
- Download web page using the `requests` library
- Parse HTML using `BeautifulSoup`
- Extract financial tables and build a structured `DataFrame`
- Clean and prepare the data

---

### 🔹 Part 2: Extracting Stock Data using Python Library (`yfinance`)

In this part, we use the `yfinance` library to programmatically extract data for public companies.

**Tasks:**
- Extract general stock info (name, ticker, sector)
- Retrieve historical share price data
- Fetch historical dividends
- Store results as `pandas` DataFrames for further analysis

---

### 🔹 Part 3: Analyzing & Visualizing Stock Data

We combine web-scraped and API-extracted data to analyze company revenue and visualize stock trends.

**Companies Analyzed:**
- Tesla (TSLA)
- GameStop (GME)
- Amazon (AMZN)
- AMD

**Tasks:**
- Use `yfinance` to extract and plot stock prices
- Use web scraping to extract revenue data for Tesla and GameStop
- Clean, merge, and format datasets
- Visualize stock price trends and revenue using `matplotlib`

**Visualizations:**
- Line charts of historical stock prices
- Revenue trend graphs for Tesla and GameStop
- Overlayed plots comparing stock price and revenue

---

## 📈 Key Learnings

- Practical web scraping with BeautifulSoup
- API data extraction using `yfinance`
- Real-world data cleaning and transformation
- Visualization techniques for financial datasets
- Hands-on experience in integrating multiple data sources

---

## 📎 Sample Output

<img src="screenshots/tesla_stock_plot.png" alt="Tesla Stock Plot" width="600"/>
<img src="screenshots/gamestop_revenue_plot.png" alt="GameStop Revenue Plot" width="600"/>

---

## 📂 Files Included

- `part1_web_scraping.ipynb`
- `part2_yfinance_data.ipynb`
- `part3_stock_visualization.ipynb`
- `/screenshots/` (plots and graphs)
- `README.md`

---

## 🚀 Future Improvements

- Add interactive dashboards using Plotly or Dash
- Expand to other sectors or indices (e.g. S&P 500, Nasdaq)
- Include machine learning to forecast stock prices

---

## 🧠 Author Note

This project is part of my IBM Data Analyst learning journey and can be found publicly on my GitHub portfolio. It showcases practical skills in data gathering, cleaning, and analysis — all essential to a Data Analyst role.

