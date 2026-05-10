# News Sentiment Analysis - Week 1

## Project Overview
This project analyzes the relationship between financial news sentiment 
and stock price movements for Nova Financial Solutions.

We analyze over 1.4 million news headlines and historical stock price 
data for companies including AAPL, AMZN, GOOG, META and NVDA.

## Setup Instructions

### 1. Clone the repository
git clone https://github.com/rah-salah/news-sentiment-analysis.git
cd news-sentiment-analysis

### 2. Create virtual environment
python -m venv .venv

### 3. Activate environment
Windows:
.venv\Scripts\activate

### 4. Install dependencies
pip install -r requirements.txt

## Project Structure
- notebooks/ - Jupyter notebooks for analysis
- data/raw/ - Raw datasets (not uploaded to GitHub)
- src/ - Source code
- tests/ - Test files
- scripts/ - Utility scripts
- .github/workflows/ - CI/CD pipeline

## Data Sources
- Financial News Dataset (FNSPID) - 1.4 million headlines (2009-2020)
- Historical Stock Prices - Daily OHLCV data via YFinance

## Notebooks
- eda.ipynb - Exploratory Data Analysis on news dataset
- task2.ipynb - Technical indicator analysis on stock data
