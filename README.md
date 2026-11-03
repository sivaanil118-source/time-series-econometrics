# Time-Series Econometrics in Python

A compact, reproducible walkthrough of core time-series econometric methods using **Python, NumPy, pandas and statsmodels**.
Every section simulates data with known properties, so each test result can be checked against the true data-generating process.

## Contents

| # | Topic | Methods |
|---|-------|---------|
| 1 | OLS from first principles | slope via Cov/Var, RSS, TSS, R² |
| 2 | Residual autocorrelation | Breusch–Godfrey LM test |
| 3 | Stationarity | white noise, random walk, deterministic trend, ADF test, differencing |
| 4 | Spurious regression | independent random walks, Durbin–Watson warning |
| 5 | ARMA / ARIMA | AR(1), MA(1), ARMA(1,1), ACF/PACF, ARIMA estimation, AIC |
| 6 | Cointegration | Engle–Granger two-step, Error-Correction Model |
| 7 | VAR | lag selection, Granger causality, forecasting |

## Run it

```bash
pip install -r requirements.txt
jupyter notebook time_series_econometrics.ipynb
```

## About

Siva — M.Sc. Quantitative Finance, Kiel University (CAU).
Interests: financial econometrics, volatility modelling, energy markets.

   Built from my own course exercises in Econometric Methods. Code was refactored and documented with AI assistance (Claude); I reviewed every section and checked each result against the known simulated values.
