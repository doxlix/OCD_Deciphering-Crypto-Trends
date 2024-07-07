# [Deciphering Crypto Trends: Google Trends Analysis and Predictive Modeling](https://competitions.desights.ai/challenge/24)
## Overview

This report analyzes the relationship between various sentiment indicators and cryptocurrency prices, focusing on:

1. Google Trends data
2. Fear and Greed index
3. Twitter activity
4. News sentiment

The analysis aims to identify correlations, patterns, and potential predictive indicators for cryptocurrency price movements.

## Methodology

- **Data sources**: Google Trends, cryptocurrency price and volume data, Fear and Greed index, Twitter data, news articles
- **Time frame**: Multiple cryptocurrency cycles, with a focus on the 2nd and 3rd Bitcoin halving cycles
- **Analysis techniques**: 
  - Correlation analysis
  - Time lag analysis
  - Exploratory data analysis
  - Machine learning models (Linear Regression, Random Forest, Feedforward Neural Network)

## Key Findings

1. Google Trends ratings show a strong correlation (94% on average) with cryptocurrency prices.
2. Most cryptocurrency prices are closely tied to Bitcoin's price movements.
3. No significant time lag exists between price movements and changes in Google Trends ratings.
4. Google Trends ratings don't always follow price movements, especially in rare negative events.
5. Tweet volume doesn't consistently correlate with price movements for most cryptocurrencies.
6. Linear Regression and Feedforward Neural Networks performed best in predicting Google Trends ratings.

## Machine Learning Models

Three models were built to predict Google Trends ratings:

1. Linear Regression
2. Random Forest
3. Feedforward Neural Network

Models were tested with and without feature engineering, using ADA as the test case due to its high Trend/Volume and Trend/Price correlation.

## Conclusion

While sentiment indicators, particularly Google Trends data, show strong correlations with cryptocurrency prices, their predictive power varies. The report suggests that a combination of indicators and advanced machine learning techniques could potentially improve prediction accuracy.

## Additional Resources

The report includes detailed analyses of cryptocurrency cycles, correlation matrices, and visualizations of various sentiment indicators.

For more information on the data sources and specific methodologies, refer to the "Data sources" section in the full report.
