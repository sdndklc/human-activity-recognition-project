#Human Activity Recognition  

This repository includes classification of human activity by using data taken from smartphone.

This dataset contains 7 activity, 10300 samples and 561 smartphone data.

LSTM, MLP and RNN models are used for classification.

- LSTM consist of one LSTM layer and one linear layer. Cross entropy loss is used as loss function. It gives % 99.32 accuracy. 
- Multilayer perceptron (MLP) consists of 3 layers ReLu and LogSoftmax activation functions are used between these layers. Cross entropy loss is used as loss function. It gives % 99.05 accuracy. 
- Reccurrent neural network (RNN) consist of one RNN layer and one linear layer. Cross entropy loss is used as loss function. It gives % 99.42 accuracy. 

Confusion matrix and precision, recall, f1 scores are used as model evalution metric.
