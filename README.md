# Cryptocurrencies-Price-Prediction-using-LSTM-Neural-Network-model
Empirical study on applying Long Short-Term Memory (LSTM) model to predict five major cryptocurrencies that are: Bitcoin (BTC), Ethereum (ETH), Cardano (ADA), Solana (SOL) and Polkadot (DOT).

The purpose of this research is to forecast the price of five different cryptocurrencies through a Long Short-Term memory approach and evaluate the accuracy of the prediction. The cryptocurrency market is heavily influenced by a multitude of variables, which makes digital assets extremely volatile. However, thanks to the enormous volume of data available, a detailed study using the proper neural network algorithm model will provide a precise price prediction. Therefore, the empirical project proposed is focused on price and consider it as a variable for forecasting. For this goal, a LSTM model is developed. The latter does not predict the future, but it can suggest a broad trend and the overall direction in which to expect price movement of the cryptocurrencies utilized. 

The methodological approach is divided in different stages. The whole process starts from collecting data from an online market data provider (Yahoo Finance). The dataset includes five cryptocurrency close prices based on USD currency with a daily frequency. The historical data prices go from the 1st January, 2021 to the 1st September, 2022. 

Filtering and cleaning the data set is the second phase. This step involves removing and replacing all the missing, empty, and non-matching data from the rows. As the model requires only the close column labelled, it is also needed to drop out unnecessary variables present in the data collected.

The next stage is the data exploration and visualisation process where, performing descriptive analysis, it is shown and explored the behaviour and distribution on data and the relationship between digital assets. 

Then, normalisation is applied to improve the performance and training stability of the model. This is reached transforming features to be on a similar scale. 

The further step is splitting the dataset into training and testing parts. In order to estimate the future price of cryptocurrencies, the model is trained using the algorithm and the features considered to assist the model. After testing data, we evaluated the accuracy of the algorithm that the LSTM model is using to forecast the price of the different digital assets selected. 

