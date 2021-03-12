# Water-Hackathon-2021
All about my model, data and result visualization code is in my .ipynb files. The forecasting method used here is Seasonal Autoregressive Integrated Moving-Average, or SARIMA for short. I ran the model on two data series, which located in two different sheets of the Water-data.xlsx file. I get the data from here: https://archive.ics.uci.edu/ml/datasets/water+treatment+plant

The forecast model ran on DQO data predicts COD level (in mg/L) with RMSE=74.61, while forecast model ran on SSV data predicts volatile suspended solid level (in mg/L) with RMSE=6.56.

The validation forecast plots show how fit the prediction to the existing data. I set a validation start date, on July 1st 1990 for more specific. The model gives prediction from that day, then compares to the actual existing data.

The future forecast plots show the forecast of the model in the unobserved future. The forecast results are saved in the excel files ( *_prediction.xlsx)

I saved all the necesary plots to .png files for downloading.
