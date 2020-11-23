# Deep_Learning_Simulation

In this simulation we compared two LSTM models to predict Bitcoin closing price. One model used a 10-day window of the Fear and Grred (FNG) index to predict the 11th day's closing price. The other model used a 10-day windo of Bitcoin's closing price to predict the 11th day's closing proce. Both models used all of the same parameters for comparison purposes.

## FNG Index LSTM Model vs. Closing Price LSTM Model

The model that used the FNG index to predict Bitcoin closing price did not perform well. It could not accurately predict Bitcoin's closing price. This suggest that the FNG alone is not a good indicator to predict how Bitcoin will fluctuate in price. The Closing Price LSTM model performed very well. The graph that was generated shows that the predicted close prices where very close to the actual close price. That being said, I believe that as new data becomes available it would need to be fed into the model in order for it to continue to perform well.

## Oerall Conclusions

While the LSTM model that used only previous close prices of Bitcoin to predict future close prices performed well, we need to keep in mind that other factors do effect the close price besides the previous close price. In order to have the most accurate model more data, especially data that would impact the future prices of Bitcoin, would need to be included in a model that would be designed to predict Bitcoin closing price. We need to remember that past performance is not a sure indicator of future performance.