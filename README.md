# 📈 Stock and Revenue Data Analysis Dashboard for Tesla and GameStop

This project demonstrates how to use Python libraries to extract, clean, and visualize historical stock and revenue data for **Tesla (TSLA)** and **GameStop (GME)**. It leverages data from Yahoo Finance and web scraping to create interactive dashboards using Plotly.

---

## 🚀 Features

- Extract stock price data using `yfinance`
- Scrape quarterly revenue data using `BeautifulSoup` and `requests`
- Clean and transform financial data using `pandas`
- Create interactive dashboards with `plotly.graph_objects`
- Visualize trends in stock prices and revenue over time

---

## 🛠️ Technologies Used

- Python 3
- Pandas
- YFinance
- BeautifulSoup (bs4)
- Requests
- Plotly

---

## 📊 Visual Output

- 📈 Line chart of stock prices (Tesla & GameStop)
- 📊 Bar chart of quarterly revenue
- 📆 Time range slider for better analysis

---

## 📂 Project Structure

```
.
├── Stock and Revenue Data Analysis Dashboard for Tesla and GameStop.ipynb
├── README.md
```

---

## 📥 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/tesla-gamestop-dashboard.git
   cd tesla-gamestop-dashboard
   ```

2. Install dependencies:
   ```bash
   pip install yfinance pandas plotly requests beautifulsoup4
   ```

3. Open the notebook:
   ```bash
   jupyter notebook
   ```

4. Run the cells in the notebook to extract data, process it, and generate the dashboards.

---

## 📌 Data Sources

- [Yahoo Finance](https://finance.yahoo.com/)
- Tesla Revenue Table: Embedded HTML from [revenue.htm](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/revenue.htm)
- GameStop Revenue Table: Embedded HTML from [stock.html](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/stock.html)

---

## 📃 License

This project is part of the IBM Skills Network Data Science and Python Certification Course. For educational use only.
