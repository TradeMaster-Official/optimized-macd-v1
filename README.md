# Optimized MACD Indicator

Welcome to the **Optimized MACD Indicator**! This Pine Script indicator is designed to provide a more responsive and customizable Moving Average Convergence Divergence (MACD) indicator for your trading strategies.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Alerts](#alerts)
- [License](#license)

## Overview

The Moving Average Convergence Divergence (MACD) is a trend-following momentum indicator that shows the relationship between two moving averages of a security’s price. This optimized version allows for greater flexibility and customization to suit various trading styles.

## Features

- **Customizable Fast and Slow Lengths**: Adjust the periods for the fast and slow moving averages.
- **Source Selection**: Choose the source of the data (e.g., close, open, high, low).
- **Signal Smoothing**: Configure the smoothing period for the signal line.
- **Oscillator and Signal Line MA Types**: Select between Simple Moving Average (SMA) and Exponential Moving Average (EMA) for both the oscillator and signal line.
- **Visual Alerts**: Background color changes to indicate buy and sell signals.
- **Alert Conditions**: Set alerts for when the MACD histogram switches from rising to falling and vice versa.

## Installation

To use this indicator in TradingView:

1. Open TradingView and navigate to the Pine Script editor.
2. Copy and paste the code from `macd.opt.pine` into the editor.
3. Save the script and add it to your chart.

## Usage

Once the indicator is added to your chart, you will see the MACD and Signal lines plotted along with the histogram. The background color will change based on the histogram values to indicate potential buy and sell signals.

## Configuration

You can customize the indicator using the following inputs:

- **Fast Length**: The period for the fast moving average (default: 3).
- **Slow Length**: The period for the slow moving average (default: 12).
- **Source**: The data source for the moving averages (default: close).
- **Signal Smoothing**: The period for smoothing the signal line (default: 9).
- **Oscillator MA Type**: The type of moving average for the oscillator (options: SMA, EMA; default: EMA).
- **Signal Line MA Type**: The type of moving average for the signal line (options: SMA, EMA; default: EMA).

## Alerts

The indicator includes built-in alert conditions to notify you of potential trading signals:

- **Rising to Falling**: Triggered when the MACD histogram switches from rising to falling.
- **Falling to Rising**: Triggered when the MACD histogram switches from falling to rising.

To set up alerts in TradingView:

1. Right-click on the chart and select "Add Alert".
2. Choose the desired alert condition from the list.
3. Configure the alert settings and save.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Happy trading! 🚀
