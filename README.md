# Financial Planning Tools

This is a collection of two financial planning tools that enable credit union members to 1. visualize their savings and determine if they can start an emergency fund and 2. help members with financial planning for retirement using Monte Carlo simulations.

---

## Technologies

This project leverages python with the following packages:

* [pandas](https://github.com/pandas-dev/pandas) - For plotting, dataframes, and calculations.

* [dotenv](https://pypi.org/project/python-dotenv/) - For accessing the .env file.

* [alpaca-trade-api](https://github.com/alpacahq/alpaca-trade-api-python) - For financial data from [Alpaca](https://alpaca.markets)

* MCForecastTools - For Monte Carlo simulations. For documentation, use ?MCSimulation

---

## Installation Guide

Before first running the application install the following dependencies.

```python
    pip install pandas
    pip install python-dotenv
    pip install alpaca-trade-api
```

Jupyter may be required to view the .ipynb file.

```python
    pip install jupyter
```

The MCForecastTools.py included contains everything needed for the Monte Carlo simulations.

This application also utilizes a .env file in order to store API keys and secret keys for the Alpaca API & SDK. In order to use this, you must create a .env file and set it up like the following:

```
ALPACA_API_KEY = "<Your API Key Here>"
ALPACA_SECRET_KEY = "<Your Secret Key Here>"
```
---

## Usage

Usage is primarily viewing data and visuals but can be repurposed to intake different data. This allows the user to create their own portfolio with up-to-date information and run Monte Carlo simulations to help determine potential investment plans.

---

## Contributors

Brought to you by Majid Kouki. You can reach me at [majidkpy@gmail.com](mailto:majidkpy@gmail.com).

---

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
