## Stock Market Prediction
To create *Stock Market* model using extended version of Recurrent Neural Network (RNN). <br>
Extended version due to special feature capable of learning long term dependencies. <br>
LSTMs are explicitly designed to avoid the long-term dependency problem which occurs in RNN as <br>
*Vanishing Gradient Problem*.

![](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSVFfyOohG8h_o66A47Y5fEfoAiuvFzH2EubMpbNcAeqmxNDyFZ)

> *ARIMA algorithm can be also trained for the same but yields better results in forecasting short term, where <br> 
as LSTMs have input gates that control whether or not the input at each time step is added to the cell state. This means that the LSTM can be trained to add a certain input to its cell state, and then never activate again, which preserves the cell state indefinitely. <br>
In short LSTM have 10x more Long Term Memory than RNN.*

*Dataset can be found [here](http://quotes.wsj.com/GOOG/historical-prices/download?MOD_VIEW=page&num_rows=6299.041666666667&range_days=6299.041666666667&startDate=09/06/2000&endDate=12/05/2017)*

## Reference
https://stackoverflow.com/questions/45435049

## Author
- Prasad Patil
