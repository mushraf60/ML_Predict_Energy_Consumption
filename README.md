# ML_Predict_Energy_Consumption

Time Series Forecasting (LSTM)

With the growing global emphasis on energy efficiency and sustainability, accurate prediction of energy consumption has become increasingly important. Organizations and governments are seeking data-driven solutions to optimize energy use, reduce operational costs, and minimize environmental impact. In this context, machine learning offers powerful tools for modeling and forecasting energy demand based on historical data and influential factors.This project aims to develop a machine learning model capable of predicting future energy consumption using past usage patterns and relevant external variables such as temperature, humidity, time of day, and day of the week. By leveraging algorithms like linear regression, decision trees, or advanced methods like random forests and neural networks, the model can learn complex relationships between input features and energy usage.

Abstract

The dataset is exhaustive in its demonstration of energy consumption of the Tétouan city in Morocco. The distribution network is powered by 3 Zone stations, namely: Quads, Smir and Boussafou.
The data consists of 52,416 observations of energy consumption on a 10-minute window. Every observation is described by 9 feature columns.Training the LSTM model was done using the training set and the validation dataset for testing the results through the training process. The learning algorithm worked through the entire training dataset 60 times (Epoch), and the model weights were updated after each batch where the batch size is 20.

dataset:https://www.kaggle.com/datasets/fedesoriano/electric-power-consumption
