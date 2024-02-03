# Forecasting Net Prophet

   ### CONTENTS
**[The Challenge](#the-challenge)**<br>
**[Starter Code](#starter-code)**<br>
**[Challenge Checklist](#challenge-checklist)**<br>
**[Running the Program](#running-the-program)**<br>
**[Final Answers](#final-answers)**<br>

## The Challenge

Taking on the role of a growth analyst for [MercadoLibre](https://investor.mercadolibre.com/about-us/), a popular e-commerce site in Latin America, will analyze data and utilize Prophet to predict the future for trading its stock.

## Starter Code

The starter code for this challenge consists of a single notebook file which will run using Google's Colaboratory cloud environment. It contains more detailed instructions than past challenges both in markdown and in code comment fashion. It contains the code to setup the environment (importing/installing associated packages) along with reading in and displaying the initial and later data sets. Expected cell outputs are also included. Bits and pieces of code, analysis questions, some answers, and other odds and ends throughout the file step through the data analysis process. Finally the starter notebook ends with three questions to be answered after analysis of the data:

- What time of day exhibits the greatest popularity?
- Which day of week gets the most search traffic?
- What's the lowest point for search traffic in the calendar year?

## Challenge Checklist

### Part 1: Find Unusual Patterns in Hourly Google Search Traffic

- [x] Slice and plot the data to the month of May 2020
- [x] Calculate search traffic for May 2020 and monthly medians
- [x] Answer analysis question of search traffic related to financial release

### Part 2: Mine the Search Traffic Data for Seasonality

- [x] Group data by hour and analyze
- [x] Group data by day and analyze
- [x] Group data by week and analyze
- [x] Answer analysis question of time based trends

### Part 3: Relate the Search Traffic to Stock Price Patterns

- [x] Plot new data and concatenate to earlier data
- [x] Slice the data for first half of 2020, display, plot, and search for trends (I note the analysis question here is previously answered)
- [x] Calculate lag, volatility, and hourly returns
- [x] Review correlations (I note the analysis question here has also been previously answered)


### Part 4: Create a Time Series Model with Prophet

- [x] Setup data for Prophet forecast
- [x] Estimate model, plot the forecast, and answer analysis question of near-term forecast
- [x] Plot individual model components and answer final questions

## Running the Program

The program folder contains the completed notebook which can be run cell by cell from and results displayed in a Google Colaboratory environment available within Google Drive.

```
forecasting_net_prophet.ipynb
```

The outputs for cells in the notebook are saved with the file (just in case viewer does not wish to setup a Google Colaboratory environment in their own Google Drive). The notebook cells may be re-run from top to bottom. Standard outputs resemble those displayed in the original starter code. I also added enhanced plots using Matplotlib for easier readability and decipherability.

## Final Answers

My answers to the final three questions are also saved at the end of the notebook.