# ETF_Analyzer

The ETF Anayzer researches the performance of a hypothetical ETF consisting of four securities offered by a new fintech startup. The analysis covers a four year time period ranging from Dec 2016 - Dec 2020. The goal is to analyze the daily returns for each security individually and then analyze the securities as a whole. The data kept for each security is held in an sql database. This data will be pulled into a pandas dataframe where the analysis will take place. A Jupyter Notebook will be used to produce advanced queries and visualizations to demonstrate the analysis. Once analysis has been completed the notebook will be deployed using Voilia to make an interactive webpage. 

---

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://pandas.pydata.org/docs/getting_started/install.html) - For summary statistics, visulizations, and times series analysis.
* [hvplot](https://hvplot.holoviz.org/user_guide/Introduction.html) - A high-level plotting API for pandas, dask, xarray, and networkx built on HoloView
* [jupyter lab](https://jupyter.org/install) - JupyterLab is the latest web-based interactive development environment for notebooks, code, and data.
* [numphy](https://numpy.org/) - NumPy offers comprehensive mathematical functions, random number generators, linear algebra routines, Fourier transforms, and more.
* [sqlalchemy](https://pypi.org/project/SQLAlchemy/) - SQLAlchemy is the Python SQL toolkit and Object Relational Mapper that gives application developers the full power and flexibility of SQL.


* Visual Studio Code Version: 1.70.2 (Universal)
Commit: e4503b30fc78200f846c62cf8091b76ff5547662
Date: 2022-08-16T05:36:37.829Z
Electron: 18.3.5
Chromium: 100.0.4896.160
Node.js: 16.13.2
V8: 10.0.139.17-electron.0
OS: Darwin arm64 21.4.0

---

## Installation Guide

Before running the application first install the following dependencies.

```python
import numpy as np
import pandas as pd
import hvplot.pandas
import sqlalchemy

```

## Dataset Information 

GDOT, GS, PYPL, SQ

Data frame containing pay pal information:

pypl_dataframe

Paypal close prices higher than 200:

pypl_higher_than_200

Top ten return values for Pay Pal:

pypl_top_10_returns

Daily returns for all 4 data sets:

etf_portfolio

Average returns for the four datasets:

etf_portfolio_returns

Cumulative returns of the four datasets:

etf_cumulative_returns


---

## Contributors

#### Antiwan Maxwell
#### Contact Infromation:

email: antiwan.maxwell@outlook.com

[LinkedIn](https://www.linkedin.com/in/antiwan-maxwell-205a11233/)


---

## License

MIT
