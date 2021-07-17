# ARIMA

Auto Regressive Integrated Moving Average (ARIMA) is a generalized model that combines Autoregressive (AR) process and Moving Average (MA) processes and builds a composite model of the time series. As acronym indicates, ARIMA has the following parameters (p), (d) and (q). (p) describes the dependencies between an observation and a number of lagged observations; (d) is the differences of observations at a different time; (q) shows the dependency between observations and the residual error terms when a moving average model is used to the lagged observations 

# StackedLSTM

Long Short-Term Memory (LSTM): LSTM is a recurrent neural network with the capability of remembering the values from earlier stages and forgetting unnecessary trends decided in each cell of the network [2]. They consist of an input layer, a hidden layer, and an output layer. The hidden layer of a LSTM network contains memory cells which in turn contain three gates that are responsible for updates to its cell state. These three gates are an input gate, an output gate, and a forget gate. Stacked LSTM networks provide a deeper model for learning and are composed of multiple hidden layers of LSTMs as in figure 2. These multiple hidden layers act as a Deep Recurrent Neural Network![7  Stacked LSTM model](https://user-images.githubusercontent.com/61934483/126032148-6f373dca-0c57-4e5b-961e-4088cb32e1f7.jpg)

### Bibliography
* Ojo, S. O., Owolawi, P. A., Mphahlele, M., & Adisa, J. A. (2019, November). Stock market behaviour prediction using stacked LSTM networks. In2019 International Multidisciplinary Information Technology and Engineering Conference (IMITEC) (pp. 1-5). IEEE.
* Siami-Namini, S., Tavakoli, N., & Namin, A. S. (2018, December). A comparison of ARIMA and LSTM in forecasting time series. In 2018 17th IEEE International Conference on Machine Learning and Applications (ICMLA) (pp. 1394-1401). IEEE
