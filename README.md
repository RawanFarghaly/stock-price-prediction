# Stock Price Prediction Model

A machine learning project that predicts stock prices from historical market data using **Linear Regression**, built in Python with Google Colab.

## Overview

This project walks through a complete predictive-modeling workflow: cleaning historical stock data, exploring it, engineering and scaling features, training a regression model, and evaluating how close its predictions are to the actual prices.

## Workflow

1. **Data cleaning**: handling missing values and inconsistencies in the historical dataset.
2. **Exploratory data analysis (EDA)**: studying price trends and the relationships between features using visualizations.
3. **Feature engineering and scaling**: preparing and scaling the features used to train the model.
4. **Modeling**: training a Linear Regression model on the training split.
5. **Evaluation**: measuring performance on a held-out test set and plotting actual vs. predicted prices.

## Results

Evaluated on the held-out test set:

| Metric | Value |
|--------|-------|
| MAE    | 0.4498 |
| MSE    | 0.4694 |
| RMSE   | 0.6852 |

The notebook also includes a line plot comparing actual and predicted prices.

## Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## How to Run

1. Open the notebook from this repository in Google Colab (or Jupyter Notebook).
2. Make sure the dataset file is available, or update the data path in the first cells.
3. Run all cells from top to bottom (**Runtime > Run all** in Colab).

To run locally, install the dependencies first:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Limitations

Stock prices are influenced by many external factors such as news, market sentiment, and economic events, while Linear Regression captures only linear relationships in historical data. This project is a learning exercise and **should not be used for real investment decisions**.

## Author

**Rawan Ahmed**: Computer and Control Engineering student, Suez Canal University
[LinkedIn](https://www.linkedin.com/in/rawan-ahmed-7584b429a/) | [GitHub](https://github.com/RawanFarghaly)
