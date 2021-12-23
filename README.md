# Fintech Challenge 04 -- Portfolio Risk & Return Analysis

An analysis of portfolio risk and return.

---

## Analysis 

#### DataSets
Daily  Soros, Tiger, Paulson and Berkshire, were analyzed against the S&P 500, over the period of Oct 2014 -> Sept 2020. The data source can be found in [whale_navs.csv](./Resources/whale_navs.csv).


#### Assumptions

Each fund was analyzed for performance, volatility, risk, risk-return profile, and portfolio diversity against the S&P 500. 

When calculating the Sharpe Ratios, it was assumed that the risk-free rate is essentially zero.

When doing the portfolio diversification analysis, the two portfolios with the highest Sharpe ratios were chosen to analyze.

#### Summary

In short, the BERKSHIRE HATHAWAY INC fund had the highest cumulative return, the highest sharpe ratio, and a modest rolling beta compared to the S&P500, so it was the recommended portfolio fund.

See details and visualizations in the notebook [risk_return_analysis.ipynb](./risk_return_analysis.ipynb)

---

## Technologies

This challenge uses [python](https://www.python.org/) 3.7 and the following [built-in](https://docs.python.org/3/py-modindex.html) modules:
- [pathlib](https://docs.python.org/3/library/pathlib.html#module-pathlib)

Additionally, it requires:
- [matplotlib](https://matplotlib.org/)
- [pandas](https://pandas.pydata.org/)
- [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/)
- [seaborn](https://seaborn.pydata.org/tutorial.html)
- [numpy](https://numpy.org/)

See [installation](#installation) below for specifics.

---

## Installation

You will need Python 3.7, that supports for this application to run. An easy way to install python 3.7 is to download and install [Anaconda](https://www.anaconda.com/products/individual). After installing anaconda, open a terminal/command-prompt, and setup a python 3.7 environment, and then activate it like so:

```
# create an anaconda python 3.7 environment
# name can be any friendly name to refer to your environment, eg 'dev'
conda create --name dev python=3.7 anaconda

# activating the environment
conda activate dev
```

---

## Usage

The analysis is presented within a [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) notebook. To launch JupyterLab, from the root of this repo dirctory:

```
# within repo root 
$ jupyter lab
```
You can now open the notebook [risk_return_analysis.ipynb](./risk_return_analysis.ipynb) locally with JupyterLab.

---

## Contributors

[David Lopez](https://github.com/sububer)

---

## License

MIT