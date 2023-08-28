# Electricity-Production-Forecast-using-RNN-and-LSTM
Time series forecast using RNN and LSTM

# Topic
In this project my goal is to forecast time series using deep learning. I used both an RNN (which only takes advantage of the short term memory) and an LSTM (which also counts in the long
term memory) to make forecasts. The dataset I used was created by using the data as an input sequence and using the data shifted by one as an output sequence. The results of the RNN were 
quite modest (it kind of gave the average over all the timesteps) but much better for the LSTM whose forecasts lined up with the actual values.

# Objetive
- Make forecasts using an RNN and LSTM

# Summary

- Loading libraries
- The data
- Plotting the data
- Creating the dataset
- Building the models
- Training the models
- Plotting the forecasts
- Conclusion

# Data source
https://www.kaggle.com/datasets/shenba/time-series-datasets?select=sales-of-shampoo-over-a-three-ye.csv&fbclid=IwAR0wkeIpmmspHeVj5hHY7aZ9aKclf8GeimWfx2a8mzLK5Qz6QaQTaW80gF0
