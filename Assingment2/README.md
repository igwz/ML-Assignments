# Assignment 2 Dataset Description

This folder contains the dataset `AAPL_Stock_Price_Dataset.csv`, which stores historical Apple stock market data.

## Dataset Overview

- File name: `AAPL_Stock_Price_Dataset.csv`
- Company: Apple Inc. (`AAPL`)
- Number of rows: 11,354
- Number of columns: 9
- Main purpose: analysis and preprocessing of Apple stock price behavior over time

Each row represents one trading day.

## Columns

- `Date`: trading date
- `Open`: opening stock price for the day
- `High`: highest stock price reached during the day
- `Low`: lowest stock price reached during the day
- `Close`: closing stock price for the day
- `Volume`: number of shares traded during the day
- `Daily_Return`: percentage daily return based on price change
- `Price_Range`: difference between the daily high and low prices
- `Price_Change`: difference between closing price and opening price

## Data Types

- `Date`: date/time field
- `Open`, `High`, `Low`, `Close`: numerical continuous values
- `Volume`: numerical integer value
- `Daily_Return`, `Price_Range`, `Price_Change`: numerical continuous values

## Notes

- The dataset is time-series data because observations are ordered by date.
- The first row may contain a missing value in `Daily_Return` because no previous trading day exists for return calculation.
- The dataset can be used for cleaning, preprocessing, visualization, outlier detection, normalization, and dimensionality reduction tasks.
