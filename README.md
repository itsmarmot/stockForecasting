# Predicting Stock Prices with Python

This repository contains code and resources for a project on predicting stock prices using Python. The project is implemented in Google Colab and focuses on applying various machine learning techniques to forecast stock prices.

## **Table of Contents:**

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Data Description](#data-description)
- [Modeling](#modeling)
- [Results](#results)
- [Contributing](#contributing)

## **Introduction:**

Predicting stock prices is a complex yet intriguing task that involves analyzing historical price data and identifying patterns to forecast future prices. This project aims to leverage machine learning algorithms to predict stock prices and help investors make informed decisions.

## **Project Structure:**

The repository is organized as follows:

.
│
├── data
│   └── Data_Historis_BBNI.csv # Historical stock price data
│
├── models
│   └── scaler.pkl # Scaler object for data normalization
│
├── notebooks
│   └── Forecasting_BBNI_Stockprice.ipynb # Main project notebook
│
├── results
│   └── predictions.csv # Predicted stock prices
│
├── README.md # Project README file
│
└── requirements.txt # Python dependencies

## **Installation:**

To get started, clone the repository and install the required dependencies:

```bash
git clone https://github.com/itsmarmot/stockForecasting.git
cd stockForecasting
pip install -r requirements.txt
```

## **Usage:**

The main code for the project is contained in the Jupyter notebook `notebooks/Forecasting_BBNI_Stockprice.ipynb`. You can run this notebook in Google Colab or any local Jupyter environment.

1. Open the notebook.
2. Follow the instructions in the notebook to load data, preprocess it, train models, and make predictions.
3. The results will be saved in the `results` directory.

## **Data Description:**

The dataset used in this project consists of historical stock prices, which include features such as:

* `Tanggal`: The date of the recorded stock price.
* `Pembukaan`: The opening price of the stock on the given date.
* `Tertinggi`: The highest price of the stock on the given date.
* `Terendah`: The lowest price of the stock on the given date.
* `Terahir`: The closing price of the stock on the given date.
* `Vol.`: The trading volume of the stock on the given date.
* `Perubahan%`: the Percentage about stock price Trend Over Time

## **Modeling:**

The project employs various machine learning models to predict stock prices, including:

* Long-Short Term Memory (LSTM)
* ARIMA 
* Facebook-Prophet

## **Results:**

The predicted stock prices are saved in the `results/predictions.csv` file. The notebook also includes visualizations of the actual vs. predicted prices to help assess model performance.

## **Contributing:**

Contributions are welcome! If you have any improvements or suggestions, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
5. Push to the branch (`git push origin feature/AmazingFeature`)
6. Open a Pull Request
