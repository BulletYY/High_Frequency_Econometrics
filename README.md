# High-Frequency Econometrics & Market Microstructure in R

This repository contains R-based academic projects focused on high-frequency financial data, market microstructure, intraday seasonality, volatility modelling, and transaction-level market analysis.

The projects use transaction data to study intraday trading patterns, volatility dynamics, duration processes, and microstructure effects. The analyses include data cleaning, time aggregation, log-return calculation, descriptive statistics, intraday seasonality modelling, and preparation of high-frequency data for volatility and duration models.

## Projects

### 1. Intraday Seasonality and Volatility Modelling

**File:** `MRF_PROJEKT.html`

This project focuses on high-frequency financial data cleaning, intraday aggregation, log-return calculation, and volatility modelling. The main goal is to identify and remove strong intraday seasonality before estimating volatility models on high-frequency returns.

The project includes:
- cleaning raw transaction-level financial data,
- filtering trading hours,
- constructing timestamps from date and time variables,
- aggregating transactions to one-second and five-minute intervals,
- calculating volume-weighted prices,
- computing log returns,
- descriptive statistics of high-frequency returns,
- autocorrelation, skewness, and kurtosis analysis,
- cross-sectional intraday averages,
- intraday seasonality adjustment,
- Flexible Fourier Form modelling,
- Engle–Sokalska multiplicative seasonality modelling,
- preparation of data for volatility models such as GARCH, APARCH, and HARCH.

**Main topics:** high-frequency data, intraday seasonality, log returns, volatility modelling, Flexible Fourier Form, Engle–Sokalska model, GARCH-type models.

---

### 2. Market Microstructure and Duration Analysis

**File:** `Market microstructure.html`

This project studies market microstructure using high-frequency transaction data. The analysis focuses on transaction durations, price durations, intraday patterns, and the removal of deterministic intraday seasonality from duration processes.

The project includes:
- cleaning transaction-level data,
- constructing intraday timestamps,
- filtering market trading hours,
- calculating transaction durations,
- descriptive statistics of duration data,
- cross-sectional intraday averages,
- identifying intraday seasonality in trading intensity,
- removing deterministic intraday seasonality,
- constructing price duration measures,
- aggregating transactions for price-duration analysis,
- comparing intraday patterns between two companies,
- preparing duration data for econometric modelling.

**Main topics:** market microstructure, transaction durations, price durations, intraday trading intensity, seasonality adjustment, high-frequency econometrics.

---

## Repository Contents

- `MRF_PROJEKT.html` – R-based high-frequency econometrics project focused on intraday seasonality, volatility modelling, log returns, Flexible Fourier Form, and Engle–Sokalska adjustment.
- `Market microstructure.html` – R-based market microstructure project analysing transaction durations, price durations, intraday trading patterns, and seasonality removal.

## Technologies

- R
- R Markdown
- dplyr
- tidyr
- readr
- lubridate
- stringr
- purrr
- ggplot2
- moments
- rugarch
- knitr

## Main Areas

- High-frequency financial data
- Market microstructure
- Transaction-level data cleaning
- Intraday seasonality
- Volatility modelling
- Duration analysis
- Log-return analysis
- GARCH-type models
- Flexible Fourier Form
- Engle–Sokalska multiplicative model

## Notes

The repository focuses on high-frequency econometrics and market microstructure analysis. It should be interpreted as HFT-style data analysis rather than a high-frequency trading strategy repository.
