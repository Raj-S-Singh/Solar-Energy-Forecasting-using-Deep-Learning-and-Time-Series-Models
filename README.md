# Spatio Temporal Analysis of Solar Energy in India

In this project, time series and machine learning forecasting methods are used to build forecasting models for Solar parks in Rajasthan, Gujarat, Tamil Nadu, Telangana, Andhra Pradesh and Karnataka over different time horizons. The SARIMA, MLP and LSTM models were used to perform Daily, Weekly and Monthly forecasting and their results were compared using MAPE and RMSE values. Based on the results from these model a SARIMA-MLP hybrid model is contructed for weekly forecasting and its results are analyzed.




# Conclusions
1. GHI index is highly correlated to DHI, DNI, Clearsky GHI, Clearsky DNI, Clearsky DHI and Temperature.
2. From the time series decomposition, we can clearly see there is a clear seasonalcomponent in GHI.
3. The solar sites situated in Rajasthan, Andhra Pradesh and Tamil Nadu had higher median GHI values than solar sites in Karnataka, Gujarat and Telangana.
4. Solar site situated in Andhra Pradesh had least coefficient of variance followed by Rajasthan, but the number of outliers in Andhra Pradesh dataset is greater than Rajasthan.Gujarat and Karnataka had almost identical coefficient of variance.Telangana had the greatest coefficient of variance.
5. The SARIMA model performs best for the monthly dataset for all states except Gujarat which MLP model gave best predictions.The most accurate results were obtained for solar site located in Rajasthan.
6. For the weekly dataset, LSTM models outperform all the other models. Again the most accurate predictions were obtained for Rajasthan.
7. For the daily dataset, the predictions of LSTM and MLP models give similar results. Solar sites in Andhra Pradesh and Rajasthan had most accurate results from MLP model, while Tamil Nadu and Telangana favoured LSTM model. Karnataka and Gujarat had similar results from LSTM and MLP models.The most accurate results were obtained from the solar site in Andhra Pradesh.
8. The SARIMA-MLP hybrid models outperformed LSTM model for weekly dataset of all the states. 
9. Conducting visual analysis on the SARIMA-MLP model of Rajasthan shows that majority of the occurrences where SARIMA predictions are preferred over MLP predictions occurred during theMonsoon season of Rajasthan.(Scatter plot in Report's Appendix).
10. The MLP models hadthe least training times in comparison to the other models while the LSTM model had thegreatest training time for the above datasets.
