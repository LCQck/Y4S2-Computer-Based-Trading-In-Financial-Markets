# Y4S2-Computer-Based-Trading-In-Financial-Markets 

This repository contains various resources and strategies for computer-based trading in financial markets. The materials include datasets, backtesting scripts, strategy implementations, and a comprehensive backtest report.

## Table of Contents

- [Overview](#overview)
- [Datasets](#datasets)
- [Backtesting](#backtesting)
- [Strategies](#strategies)
- [Report](#report)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository is designed to provide tools and examples for implementing and backtesting trading strategies. It includes several datasets for different stocks, backtesting scripts, and a detailed report on the results of various trading strategies.

## Datasets

The `Datasets` folder contains historical stock price data for the following companies:
- INTC (Intel Corporation)
- MO (Altria Group, Inc.)
- O (Realty Income Corporation)
- PM (Philip Morris International Inc.)
- SPX (S&P 500 Index)
- XOM (Exxon Mobil Corporation)

These datasets are in CSV format and include daily closing prices, volumes, and other relevant information.

## Backtesting

The `Back testing.ipynb` notebook demonstrates the backtesting of different trading strategies using the provided datasets. It includes the implementation of Bollinger Bands strategy, performance evaluation, and risk assessment.

## Strategies

The `other strategies` folder contains various strategy implementations:
- `Custom Indicators in Backtesting.py.ipynb`: A notebook for using custom indicators in backtesting.
- `DCA .ipynb`: Implementation of Dollar-Cost Averaging (DCA) strategy.
- `Multi-timeframe RSI Strategies.ipynb`: Strategies based on Relative Strength Index (RSI) across multiple timeframes.
- `Quick Start User Guide.ipynb`: A quick start guide for using the backtesting framework.
- `Trading with Machine Learning Models.ipynb`: Applying machine learning models to trading strategies.

## Report

The `Backtest Report.pdf` provides a detailed analysis of the backtesting results, including performance metrics, risk assessment, and visualizations. It covers the evaluation of different strategies and their effectiveness in various market conditions.

## Usage

To use the resources in this repository:
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```
2. Navigate to the repository directory:
    ```bash
    cd your-repo-name
    ```
3. Install the required dependencies (e.g., using `pip` or `conda`).
4. Open the Jupyter notebooks to explore and run the backtesting scripts.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue if you have any suggestions or find any bugs.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
