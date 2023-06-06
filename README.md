# sales_usd
![image](https://github.com/AnkurKumarShukla/sales_usd/assets/80956033/d5d2927b-e650-4053-9b8d-f523923928d1)

# Model Training:

The training data is prepared by considering a sequence length of 30, i.e., 30 previous days' data points are used to predict the sales USD for the next day.
The input data is reshaped to match the expected input shape of the **LSTM model.**
The LSTM model is constructed with two LSTM layers and a dense output layer.
The model is **compiled with the Adam optimizer** and the mean squared error loss function.
The model is trained for 50 epochs using a batch size of 32.



# **Future Work**
We are working on making model more robust and more accurate by integration of most advance pretrain project by Facebook (now Meta) - Neural Prophet in order to have better capturing the underlying trend and demand supply. We are also in queue to implement the Bayssian neural network in order to make model which would have capability of self analysing the prediction made by them
