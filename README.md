# Foreign Exchange Rate Forecasting Using Statistical and Deep Learning Models

The project explores the modeling and forecasting of the EUR/USD exchange rate using both statistical time series methods and deep learning architectures. Motivated by the Meese-Rogoff Puzzle—which suggests that no model significantly outperforms a random walk in medium-term exchange rate forecasting—we implemented and evaluated a variety of models to assess their predictive power.

## Methods
•	Statistical Models: ARMA models of varying orders, including SARIMAX configurations and high-order lag structures.

•	Deep Learning Models:
 •	Simple dense networks
 •	LSTM-based Recurrent Neural Networks (RNNs)
 •	Convolutional Neural Networks (CNNs)
 •	Facebook’s Prophet model

 ## Key Findings
 •	Statistical models: High-order ARMA models provided reasonable fits but did not significantly outperform the random walk in out-of-sample tests.
 •	Deep learning models: Despite modeling long-term dependencies, most architectures underperformed the baseline random walk model.
 •	Best performer: Facebook’s Prophet model outperformed other deep learning models but still fell short of beating the random walk.

## Conclusion
Exchange rate forecasting remains a challenging task due to non-stationarity, long memory, and noise in FX time series. While traditional time series models offer interpretability, deep learning models may require more complex architectures and additional data (e.g., macroeconomic indicators) for improvement.





 
