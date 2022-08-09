# Title
S&P 500 Prediction using RNNs and Multi-Linear Regression

## Description
This project uses Multiple Linear Regression and Recurrent Neural Networks to predict the S&amp;P 500.RNNs are a class of Artificial  Neural Networks (ANNs) with recurrent connections. RNNs capture the temporal relationship between input/output sequences by introducing feedback to FeedForward (FF) neural networks.The RNNs of interest are Long Short Term Memory (LSTM), Bidirectional LSTM, and Gated Recurrent Unit (GRU). The best performing RNN model is selected for comparison against the Multiple Regression model's performance.

## Data Pre-Processing
The dataset consists of a total of five predictor variables namely: Gross Domestic Product(GDP), Federal Funds Rate (FFR), Money Supplied (MS), Ulcer Index (UI), and Gas Price. The response variable, y, is the S&P 500, which is a market-capitalization-weighted index of the top 500 leading publicly traded companies in the U.S. 
Before beginning the analysis, the data was preprocessed to ensure accuracy, consistency, and completeness. The first step in data preprocessing  is data cleansing. This entails checking the dataset for missing values and either removing or replacing them. The dataset was inspected for null values and none was found to be present. White spaces were removed from the dataset to make it easier for Python to read the data. The next step is data integration. This involves combining multiple data sources into a single dataset. The spreadsheet containing gas price data was merged with that containing the rest of the variables. Once this step was completed, data exploration commenced.

## Correlation Analysis
A correlation heat map was plotted to pictorially depict the relationship between the variables. In addition, a correlation matrix was created. This shows the coefficients of  correlation between the variables. The goal is to determine which variables are highly correlated and consequently eliminate one or more of the variables to prevent issues associated with multicollinearity.