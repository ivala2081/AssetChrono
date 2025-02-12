# AssetChrono

**AssetChrono** is a comprehensive asset chronology analysis tool designed to give day traders a competitive edge. By leveraging advanced statistical methods, Fourier analysis, seasonal decomposition, and machine learning techniques, AssetChrono distills complex intraday and daily market data into actionable insights. This cheat sheet is built for key market assets including the Dow Jones, Nasdaq, S&P 500, Gold, Silver, Brent Crude, and DAX.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

In today's fast-paced financial markets, timing is critical. **AssetChrono** provides an advanced, multi-timeframe analysis to help traders:
- Identify optimal trading windows by analyzing intraday return patterns.
- Understand daily seasonality using long-term historical data.
- Discover cyclical patterns with Fourier analysis.
- Leverage seasonal decomposition (STL) for trend insights.
- Generate a detailed cheat sheet summarizing the best and worst trading hours, days, and months for each asset.

By offering clear, well-designed plots and robust statistical analysis, AssetChrono empowers traders to make informed decisions and optimize their strategies.

## Features

- **Intraday Analysis:**  
  Analyze 60-minute interval data over the past month to extract hourly and day-of-week return patterns.

- **Advanced Statistics:**  
  Compute metrics such as mean, median, standard deviation, skewness, and kurtosis for precise insights.

- **Fourier Analysis:**  
  Uncover dominant cyclical frequencies in hourly returns to reveal hidden market rhythms.

- **Daily Seasonality Analysis:**  
  Use 5 years of daily data to analyze monthly and weekday patterns and perform STL decomposition for seasonal trends.

- **Visualizations:**  
  Generate high-quality, actionable plots using Matplotlib and Seaborn.

- **Comprehensive Cheat Sheet:**  
  Summarize all key findings in an easy-to-read format, providing a clear guide for day trading decisions.

## Installation

### Prerequisites

- Python 3.7 or higher (recommended)
- A virtual environment (optional, but recommended)

### Dependencies

AssetChrono relies on several Python libraries:
- numpy
- pandas
- matplotlib
- seaborn
- yfinance
- statsmodels
- scikit-learn
- scipy

### Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/AssetChrono.git
   cd AssetChrono
