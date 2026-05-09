# News Sentiment Analysis - Nova Financial Solutions

## Project Overview
* **Challenge Context**: This project is part of the 10 Academy Artificial Intelligence Mastery challenge.
* **Role**: You are a Data Analyst at **Nova Financial Solutions**, a forward-thinking financial intelligence company.
* **Objective**: The primary task is to conduct a rigorous analysis of financial news to enhance predictive analytics and forecasting accuracy.
* **Task Scope**: The pipeline involves quantifying sentiment in headlines, computing technical indicators from price data, and measuring their statistical relationship.
* **Strategic Goal**: These insights form the basis of investment strategies that use news sentiment as a predictive tool for stock market trends.

## Interim Status (As of May 10, 2026)
* **Submission Deadline**: This interim submission is prepared for the Sunday, May 10, 2026, deadline at 8:00 PM UTC.
* **Completed Work**: This repository contains the completed Task 1 (Exploratory Data Analysis) and initial progress on Task 2 (Technical Indicators).

---

## Project Structure
The project follows a modular directory structure designed for professional development and reproducibility:

```text
news-sentiment-analysis/
├── .github/workflows/       # CI/CD pipelines (unittests.yml)
├── data/raw/                # Storage for raw FNSPID and YFinance data
├── notebooks/               # Analysis and visualization notebooks
│   ├── task_1_eda.ipynb     # Completed EDA with insights
│   └── task_2_indicators.ipynb # Technical indicators implementation
├── src/                     # Source code for modular programming
├── scripts/                 # Utility scripts for data processing
├── tests/                   # Automated unit tests
├── requirements.txt         # Project dependencies
└── README.md                # Project documentation

Setup Instructions

1. Environment and Version Control
Repository: Hosted on GitHub with a specific task-1 and task-2 branch workflow.

Virtual Environment: A Python virtual environment is used to manage dependencies listed in requirements.txt.

CI/CD: Configured via GitHub Actions to run automated tests on every push.

Workflow: Commits are made at least three times a day using descriptive messages following Conventional Commits.

2. Exploratory Data Analysis (Task 1)
The analysis uncovered patterns in the Financial News and Stock Price Integration Dataset (FNSPID):

Descriptive Statistics: Obtained character count distributions for headlines and active article counts per publisher.

Publication Trends: Analyzed news volume spikes to relate them to market events.

Topic Modeling: Utilized NLP techniques (TF-IDF/LDA) to extract significant recurring themes like "earnings beat" or "price target".

Publisher Analysis: Characterized coverage and extracted unique domains from email-based publisher names.

3. Technical Indicators (Task 2 - Initial Progress)
Quantitative analysis using YFinance and TA-Lib:

Data Preparation: Cleaned and correctly typed daily trading data (Open, High, Low, Close, Volume).

Moving Averages: Implemented Simple Moving Average (SMA) and Exponential Moving Average (EMA).

Visualizations: Closing prices are overlaid with moving averages to detect trend shifts.

Technologies Used
Data Science: Pandas, Scikit-learn, TA-Lib, PyNance.

NLP: TextBlob, NLTK (VADER).

Environment: GitHub, GitHub Actions (CI/CD), Jupyter Notebooks.