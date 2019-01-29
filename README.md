# SDN_with_Neural_Network
Ryu python SDN controller with Neural Network integration for predicting anomaly in computer network.

**Description**  
This is a part of SDN project at AGH University of Science and Technology.
The purpose of implementing Deep Neural Network in SDN controller is to predict future bandwidth usage in the network and estimate confidence intervals for decision making algorithm (is there anomaly in the network?).

Neural network model (predict 60s traffic based on 600s sample) [LSTM_SDN_seconds_bayesian_60s](https://github.com/amasend/SDN_with_Neural_Network/blob/master/LSTM_models_training_jupyter/LSTM_SDN_seconds_bayesian_60s.ipynb "Title")  
Neural Network model (predict 30min traffic based on 5h sample) [LSTM_SDN_dropout_wd_30min_sigma](https://github.com/amasend/SDN_with_Neural_Network/blob/master/LSTM_models_training_jupyter/LSTM_SDN_dropout_wd_30min_sigma.ipynb "Title")  
The source for the model is taken from: [MachineLearningMastery](https://machinelearningmastery.com/how-to-develop-lstm-models-for-multi-step-time-series-forecasting-of-household-power-consumption/ "Title")  
Related work (confidence intervals in Neural Networks: [uncertainty-sense](http://www.cs.ox.ac.uk/people/yarin.gal/website/blog_3d801aa532c1ce.html#uncertainty-sense "Title")  
Related work (confidence intervals in Neural Networks: [Dropout as a Bayesian Approximation](https://arxiv.org/pdf/1506.02142.pdf "Title")  
Integration with SDN controller (change measure interval) [Ryu integration (anomaly detection)](https://github.com/amasend/SDN_with_Neural_Network/blob/master/SDN_Integration/SDN_60s_and_30min.ipynb "Title")  
Related document about time-series anomaly detection [Anomaly detection (source)](https://anomaly.io/anomaly-detection-normal-distribution/"Title")

***Environment***  
Project consists of:
- [Open source big data platform PNDA](https://github.com/pndaproject "Title") as the main point for network data collection and analysis.
- Ryu python [SDN controller](https://osrg.github.io/ryu/ "Title")
- [Mininet](http://mininet.org/ "Title") open source computer network simulation framework
- [iperf3](https://iperf.fr/iperf-doc.php "Title") network traffic generator


