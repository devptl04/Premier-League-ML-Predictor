# Machine Learning Premier League Match Predictor

## Overview

In this project, we'll predict the winner of football matches in the English Premier League (EPL) using machine learning techniques. The project involves scraping match data, cleaning and preparing the data for machine learning, making predictions using various models, and measuring the accuracy of these predictions to improve our models.

## Project Steps

1. **Scrape match data**: Using `requests`, `BeautifulSoup`, and `pandas` to gather data.
2. **Clean and prepare data**: Using `pandas` to process and clean the data for machine learning.
3. **Make predictions**: Using `scikit-learn` to build and train machine learning models.
4. **Measure error and improve predictions**: Evaluating model performance and iterating to enhance accuracy.

## Detailed Description

- Created a Python-based algorithm to predict Premier League outcomes using four seasons of historical data.
- Employed web scraping with Beautiful Soup to gather key match metrics like goals scored and conceded, and calculated rolling averages and performance metrics using Pandas.
- Designed and trained logistic regression and random forest models using `scikit-learn`, optimized with hyperparameter tuning and cross-validation.
- Created functions to predict match outcomes using expected goals and Poisson distribution for win probabilities, ultimately resulting in a 62.5% prediction accuracy.

## Code

You can find the code for this project in the following Jupyter notebooks:

- **scraper.ipynb**: A Jupyter notebook that scrapes match data.
- **predictor.ipynb**: A Jupyter notebook that makes predictions based on the scraped data.

### Tools

To create this project, I used the following tools: 

- JupyterLab
- Python 3.8+
- Python packages:
  - pandas
  - requests
  - BeautifulSoup
  - scikit-learn

Feel free to explore the code and improve the models to achieve better prediction accuracy. Happy coding!
