## Starbucks Stock Price Prediction (with EDA and Naive Forecasting)

This repository contains code for exploring and predicting Starbucks stock prices using a publicly available dataset from Kaggle: [https://www.kaggle.com/datasets/henryshan/starbucks-stock-price](https://www.kaggle.com/datasets/henryshan/starbucks-stock-price). The code is based on the work of sitilizla ([https://www.kaggle.com/code/ozlerhakan/analysis-of-starbucks-dataset](https://www.kaggle.com/code/ozlerhakan/analysis-of-starbucks-dataset)), with additional visualizations and analysis.

**Features:**

- **Exploratory Data Analysis (EDA):**
    - Visualize key statistics like total volume per year and mean price per year.
    - Analyze correlations between different features.
    - Explore the time series data of daily adjusted closing prices.
- **Naive Forecasting:**
    - Implement a naive forecasting approach to predict future prices.
    - Calculate and display Mean Squared Error (MSE) and Mean Absolute Error (MAE) for the predictions.

**Requirements:**

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- tensorflow (optional, for advanced forecasting)

**Getting Started:**

1. Clone this repository.
2. Install required libraries using `pip install -r requirements.txt` (if provided).
3. Download the Starbucks stock price dataset from Kaggle and place it in the same directory as this README file. (You might need to create a Kaggle API key to download data programmatically.)
4. Run the script `starbucks-stock-price-prediction.ipynb` using a Jupyter Notebook environment.

**File Structure:**
