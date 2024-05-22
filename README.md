# Prophet-challenge aka Mercado Libre Growth Analysis Challenge

## Background
As a growth analyst at Mercado Libre, the leading e-commerce platform in Latin America, the task is to analyze financial and user data to drive company growth. The challenge is to determine if predicting search traffic can lead to successful stock trading decisions.

## Steps Overview
1. Identify unusual patterns in hourly Google search traffic.
2. Analyze search traffic data for seasonality.
3. Correlate search traffic with stock price patterns.
4. Develop a time series model using Prophet.

## Files
- Module 8 Challenge files.

## Setup
- Create a repository named `prophet-challenge`.
- Clone the repository locally.
- Add starter files to the local repository.
- Push changes to GitHub or GitLab.
- Use Google Colab for the challenge and update the repository upon completion.

## Instructions

### Step 1: Unusual Patterns in Search Traffic
- Load search data into a DataFrame.
- Focus on May 2020, when MercadoLibre released quarterly results.
- Visualize search traffic and identify any unusual patterns.
- Calculate and compare total search traffic for May to the monthly median.
- Determine if search traffic increased during the financial results release.

### Step 2: Seasonality in Search Traffic
- Group hourly search data to find average traffic trends by hour of day.
- Group data to find average traffic by day of the week.
- Group data to find average traffic by week of the year.
- Identify any seasonal trends in search traffic.

### Step 3: Search Traffic and Stock Price Patterns
- Read and plot stock price data.
- Concatenate stock price and search data into a single DataFrame.
- Slice data to the first half of 2020 and analyze trends.
- Create "Lagged Search Trends" by shifting search traffic by one hour.
- Add "Stock Volatility" and "Hourly Stock Return" columns.
- Explore relationships between lagged search traffic, stock volatility, and stock returns.

### Step 4: Time Series Model with Prophet
- Prepare Google search data for Prophet forecasting.
- Estimate the model and plot the forecast.
- Plot time series components to determine:
  - Peak popularity times of day.
  - Busiest days of the week for search traffic.
  - Lowest points for search traffic in the calendar year.

## Hints and Considerations
- Review lesson activities for Prophet syntax and Google Colab usage.

## Requirements

### Unusual Patterns in Search Traffic
- Read search data into a DataFrame.
- Slice data for May 2020.
- Calculate total search traffic for May.
- Compare to the monthly median.
- Assess increase in traffic during financial results release.

### Seasonality in Search Traffic
- Plot average traffic by hour of day.
- Plot average traffic by day of the week.
- Plot average traffic by week of the year.
- Discuss observed time-based trends.

### Search Traffic and Stock Price Patterns
- Read and plot stock price data.
- Concatenate stock and search data.
- Slice data for the first half of 2020.
- Create "Lagged Search Trends", "Stock Volatility", and "Hourly Stock Return" columns.
- Discuss relationships between search traffic and stock metrics.

### Time Series Model with Prophet
- Set up data for Prophet forecasting.
- Plot forecast.
- Plot time series components.
- Answer questions about search traffic patterns.
