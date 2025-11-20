# Bitcoin Power Law Calculator

A modern, single-file web application to calculate the "Fair Value" of Bitcoin based on Giovanni Santostasi's Power Law theory.

![Bitcoin Power Law](https://img.shields.io/badge/Bitcoin-Power%20Law-orange)

## Overview

The **Bitcoin Power Law Calculator** is a lightweight tool that estimates the price of Bitcoin using the formula:

$$ Price = 10^{-17} \times (DaysSinceGenesis)^{5.8} $$

It provides a sleek, dark-themed interface to visualize where the current price sits relative to the model, helping users understand long-term trends.

## Features

- **Date to Price**: Enter any past or future date to see the estimated Power Law price.
- **Price to Date**: Enter a target price (e.g., $1,000,000) to find out when the model predicts it will be reached.
- **Live Data Integration**: Fetches the real-time Bitcoin price from [Mempool.space](https://mempool.space) and calculates the deviation from the model.
- **Interactive Chart**:
  - Dynamic zooming centered on your target date.
  - Visualizes the **Power Law** (Fair Value).
  - **Support Band** (0.5x) and **Resistance Band** (2.0x).
  - Plots your calculated result on the curve.
- **UX Enhancements**:
  - Thousand separators for easy price input.
  - Keyboard support (Enter key to calculate).

## How to Use

Since this is a single-file application, no installation is required.

1.  **Download** the `bitcoin_power_law.html` file.
2.  **Open** it in any modern web browser (Chrome, Edge, Firefox, Safari).
3.  **Enjoy** exploring the Power Law!

## Technologies

- **HTML5 / CSS3**: Modern, responsive design with glassmorphism effects.
- **JavaScript (ES6+)**: Core logic for calculations and API integration.
- **Chart.js**: For rendering the interactive Power Law curve.
- **Mempool API**: For fetching live Bitcoin price data.

## Disclaimer

This tool is for educational and entertainment purposes only. It is **not financial advice**. The Power Law is a theoretical model and past performance does not guarantee future results.

---
*Built with 🧡 for the Bitcoin community.*
