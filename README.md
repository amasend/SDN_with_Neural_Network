# SDN_with_Neural_Network
Ryu python SDN controller with Neural Network integration for predicting anomaly in computer network.

**Description**  
This is a part of SDN project at AGH University of Science and Technology.
The purpose of implementing Deep Neural Network in SDN controller is to predict future bandwidth usage in the network and estimate confidence intervals for decision making algorithm (is there anomaly in the network?).

First not yet integrated version is in [SDN_with_Neural_Network.](https://github.com/amasend/SDN_with_Neural_Network/blob/master/SDN_data_preprocessing_simple_NN.ipynb "Title")
Version with 30 minutes predictions for entire day is in [Convoluted 2D LSTM Encoder-Decoder model](https://github.com/amasend/SDN_with_Neural_Network/blob/master/Convolution_2D_LSTM_encode_decoder_30_min_prediction.ipynb "Title")
The source for the model is taken from: [MachineLearningMastery](https://machinelearningmastery.com/how-to-develop-lstm-models-for-multi-step-time-series-forecasting-of-household-power-consumption/ "Title")

***Environment***  
Project consists of:
- [Open source big data platform PNDA](https://github.com/pndaproject "Title") as the main point for network data collection and analysis.
- Ryu python [SDN controller](https://osrg.github.io/ryu/ "Title")
- [Mininet](http://mininet.org/ "Title") open source computer network simulation framework
- [iperf3](https://iperf.fr/iperf-doc.php "Title") network traffic generator


