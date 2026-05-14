FILE 1: README.md

````markdown
Financial News Sentiment Analysis and Stock Market Correlation

Project Overview

This project analyzes financial news headlines and historical stock market data to investigate the relationship between news sentiment and stock price movements. The project combines Natural Language Processing (NLP), Exploratory Data Analysis (EDA), and quantitative financial analysis techniques.

The main objective is to support predictive analytics and provide insight into how financial news sentiment may influence stock market behavior.

---

 Business Objective

Nova Financial Solutions aims to improve predictive analytics capabilities by analyzing financial news sentiment alongside historical stock market data.

This project helps investment teams:

- identify sentiment trends
- analyze stock volatility
- compare company performance
- investigate sentiment-return relationships
- support data-driven investment decisions

---

 Tasks Completed

 Task 1: Exploratory Data Analysis

- Headline analysis
- Publisher analysis
- Time-series news analysis
- TF-IDF keyword extraction
- Visualization of news patterns

 Task 2: Quantitative Financial Analysis

- Individual stock analysis
- SMA
- EMA
- RSI
- MACD
- Volatility analysis
- Correlation heatmaps
- Multi-stock comparison

 Task 3: Sentiment and Correlation Analysis

- Sentiment extraction using TextBlob
- Daily sentiment aggregation
- Daily return calculation
- Sentiment-return correlation analysis
- Multi-company comparative analysis

---
 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TextBlob
- TA-Lib
- Jupyter Notebook
- GitHub Actions

---

 Project Structure

```text
news-sentiment-analysis/
│
├── data/
├── notebooks/
├── src/
├── tests/
├── .github/workflows/
├── requirements.txt
├── README.md
└── .gitignore
````

---

 Installation

Clone repository:

```powershell
git clone <repository-url>
```

Create virtual environment:

```powershell
python -m venv venv
```

Activate environment:

```powershell
venv\Scripts\activate
```

Install dependencies:

```powershell
pip install -r requirements.txt
```

---

 Running the Project

Launch Jupyter Notebook:

```powershell
jupyter notebook
```

Open notebooks from the `notebooks/` folder.

---

 Key Findings

* Financial news sentiment showed measurable relationships with stock returns.
* Technology stocks demonstrated varying volatility patterns.
* Correlation analysis revealed strong relationships among major technology companies.
* NLP techniques successfully extracted sentiment information from financial headlines.
* Comparative analysis highlighted differences in market sensitivity to news sentiment.

