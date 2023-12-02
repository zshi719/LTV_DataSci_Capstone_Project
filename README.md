### Group 1: Lalla, Tilly, Victoria

# Time Series Prediction & Comparison of Covid-19 Confirmed Cases in 2020 in Two Regions of the U.S.

## Purpose of This Project
Through our analysis we aim to understand how COVID-19 cases grew and shrunk over the course of 2020. By building and comparing models for two regions in the United States (namely the Northeast and the South), we hope to see the ways various parts of the country experienced differences in COVID-19 trends. 

Our dataset contains observations from January to September of 2020 for every county in the United States. We sough to aggregate and organize our data into the region level with observations for each day per region. 

## Methodologies Employed
We each built these following 6 models to forecast the time series prediction for the NE and S regions:
- ARIMA 
- Auto-ARIMA
- Prophet Single Regressor
- Prophet Multiple Regressor
- XGBoost
- LSTM

## Layout of Github Repo
Our GitHub repo is categorized into the following directories:
- data: This folder contains the train and test data for the NE and S regions, as well as the original raw data zip
- eda: This folder contains exploratory data analysis performed on the train data
- models: This folder contains 6 sub-folders for all the models built
- preprocessing: This folder contains data preprocessing steps performed on the train data
- weekly_report: This folder contains all weekly reports

## Specific Instructions to Run Code
- To run any code that utilizes the original raw data file, user must UNZIP the original raw data in its directory first
- Each folder contains "old_ver" sub folder, which consists of older/unused work that we ran
- If a work is specifically done by one member, the file name will contain the name of the member
