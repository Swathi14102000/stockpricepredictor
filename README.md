Stock Price Prediction Web App
Overview

This is a Flask-based web application that allows users to simulate and predict stock prices using Monte Carlo simulations and visualize historical stock data. The app fetches stock prices from Yahoo Finance and provides interactive charts for historical prices, log returns, simulated prices, and histograms of predicted prices.

Features

Display historical stock prices and log returns.

Run Monte Carlo simulations to predict future stock prices.

Visualize simulated stock prices over a user-specified number of days and simulations.

Display histogram of predicted prices and calculate probability ranges.

Automatic cleanup of previously generated charts.

Technologies Used

Backend: Python, Flask

Data Analysis & Simulation: NumPy, Pandas, SciPy

Visualization: Matplotlib

Data Source: Yahoo Finance (via pandas_datareader)

Web Scraping: BeautifulSoup

Frontend: HTML templates with Flask rendering


Installation

Clone the repository

git clone https://github.com/Swathi14102000/weatherapp.git
cd weatherapp


Create a virtual environment

python -m venv venv
source venv/bin/activate   # Linux/macOS
venv\Scripts\activate      # Windows


Install dependencies

pip install -r requirements.txt

Usage

Run the Flask app:

python app.py


Open your browser and go to:

http://localhost:5000/


Enter:

Ticker Symbol (e.g., AAPL)

Number of simulation days

Number of simulations

View results:

Historical price chart

Log returns chart

Monte Carlo simulation chart

Predicted price histogram

Probability range of prices

Notes

The app automatically cleans previous output images to avoid clutter.

Make sure you have a stable internet connection for fetching stock data and scraping Yahoo Finance.
