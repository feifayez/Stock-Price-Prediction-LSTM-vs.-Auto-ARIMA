# Stock-Price-Prediction-LSTM-vs.-Auto-ARIMA
It’s challenging to accurately predict stock price as it is the result of complex interplay of various factors, such as company earning potential, macroeconomy, policy change, senior management scandal, etc. While it’s impossible for investors to foresee all aspects, we can maximize our chance by focusing on accessible information that’s predictable. For this research, we solely analyze stocks’ past price points, which are available to public, to predict their future price points. Instead of predicting closing price, we decided to focus on daily high and daily low as we believe these two features will allow investors to better plan for their buy/sell strategy. Two models were utilized for this research: LSTM neural network and auto ARIMA model. Our results show that LSTM neural network can provide satisfying prediction that’s significantly more accurate than the predicted values of auto ARIMA model which can only detect linear relationship. Also, our benchmark experiment of LSTM neural network found no evidence that more LSTM layers will lead to better model performance. Therefore, we recommend a LSTM neural network with 2 LSTM layers as our final model.
