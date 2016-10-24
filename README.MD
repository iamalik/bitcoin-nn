## Time Series Prediction with LSTM Neural Network

This is part of a project working with time series to build a predictive model around bitcoin prices. Stocks and cryptocurrency data is noisy and likely unpredictable with small amounts of data, so this is more an exercise in experimentation than a serious attempt to gain any advantage in the market.
  
Ticker data is collected on 15 second intervals, and predicted 5 minutes into the future. 

Several variations of network architecture can be used to model the data with small modifications to the layers. In it's current form, the model uses a Long Short Term Memory (LSTM) combined with a stacked neural network and dropout. LSTMs can learn long term dependencies, usually in the context of speech or text, but likewise seemed like a logical choice with which to build a time series predictor.   

The graph for this configuration is as follows:

![lstm graph] (lstm_dnn_graph.png)

More data is needed to adequately assess results, but for now, results look something like this:

```
Training Error: 0.85 RMSE
Test Error: 0.82 RMSE

Loss: 0.665656
done in 4.848s.
Overall time: 794.409s
```

![results graph] (time_series_LSTM_001.png)


Send donations to:
```
3DrXNQydchoC7aaNHa4F4BSNCL2YyZJAjn
``` 