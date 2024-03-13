# ETF Analysis and Trading Strategies: Comparing SPY and VGT ETFs

## Overview
This repository contains a detailed analysis of two Exchange-Traded Funds (ETFs): SPDR S&P 500 ETF Trust (SPY) and Vanguard Information Technology ETF (VGT). Leveraging the Alpha Vantage API, it offers insights into financial time series analysis, encompassing moving averages, return calculations, auto-correlation, Gaussianity and stationarity tests, cointegration analysis, and trading strategy development.

## Score obtained: 71 
Feedback: Good work and sufficient answers on the whole. It is nice to provide the regimes of the time series with the plots as a motivation.

## Key Features
- **Data Acquisition**: Scripts to download time series data for SPY and VGT ETFs using the Alpha Vantage API.
- **Moving Averages Analysis**: Analysis of simple moving averages (SMAs) with different time windows to spot trends.
- **Return Analysis**: Examination and comparison of linear and log returns.
- **Time Series Analysis**: Utilisation of auto-correlation functions (ACF and PACF) for price movement analysis.
- **Statistical Tests**: Gaussianity and stationarity tests on the ETFs' return series.
- **Cointegration Analysis**: Investigation of the long-term relationship between SPY and VGT ETFs.
- **Trading Strategies**: Development of trading strategies based on the analysis, focusing on pair trading under cointegration.

## Installation and Usage
### Prerequisites
- Python 3.x
- An API key from Alpha Vantage

### Libraries Required
- `pandas`
- `matplotlib`, `seaborn`
- `statsmodels`
- `alpha_vantage`

### Setup
1. Clone this repository to your local machine.
2. Install the necessary Python packages:
3. Insert your Alpha Vantage API key in the configuration file.

### Running the Analysis
Navigate to the project directory and execute the analysis scripts or Jupyter Notebooks provided.

## Contributing
Contributions to improve the analysis or trading strategies are welcome. Please refer to the issues page for existing contributions or to suggest new ones.

## License
This project is available under the MIT License. For more details, see the LICENSE file in this repository.

## Acknowledgements
- Thanks to Alpha Vantage for providing financial data APIs.
- Gratitude to IEEE for the report formatting guidelines adopted in this project.
