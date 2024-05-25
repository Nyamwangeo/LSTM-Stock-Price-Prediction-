Project Description: LSTM-Based Stock Price Direction Prediction

This project involves developing a predictive model using Long Short-Term Memory (LSTM) networks to forecast stock price directions over a three-day horizon. The data for this project is sourced from Yahoo Finance, encompassing historical stock prices and relevant financial metrics.

 Objectives:
- Predictive Analysis: Forecast whether the stock price will go up or down over the next three days.
- Model Development: Utilize LSTM networks, a type of recurrent neural network (RNN), to capture the temporal dependencies in stock price movements.

 Data Collection:
- Source: Yahoo Finance
- Data Types: Historical stock prices including open, high, low, close, and volume data.

 Methodology:
1. Data Preprocessing:
   - Retrieve historical stock data.
   - Clean and normalize the data to ensure it's suitable for training the LSTM model.
   - Create input sequences and corresponding target labels indicating the direction of price movement (up or down).

2. Model Architecture:
   - Design an LSTM network to process the sequential nature of stock prices.
   - Configure the network with appropriate layers, including LSTM layers and dense layers for final output.

3. Training:
   - Split the dataset into training and testing sets.
   - Train the LSTM model on the training data, optimizing it to minimize prediction errors.

4. Evaluation:
   - Evaluate the model's performance on the test set using metrics such as accuracy, precision, and recall.
   - Analyze the model's ability to correctly predict the direction of stock prices over the three-day period.

 Results:
- The model’s performance metrics indicate its effectiveness in predicting stock price directions, providing valuable insights for potential trading strategies.

 Future Objective:
- Explore the inclusion of additional features such as technical indicators or sentiment analysis from news articles (I must emphasize sentiment analysis as this is key to driving of prices, I already have one sentimental analysis model and looking to integrate both and see the outcomes).
- Fine-tune the LSTM model's parameters and architecture for improved accuracy (minimize MSE and RMSE).
- Consider extending the prediction horizon or applying the model to different stocks and markets.

