# PREFETCHING MEMEORY ADDRESS

In this project, a RNN model is implemented to prefetch memory address. To be more precise, using the 999 memory address to predict the 1000 memory address.

For our implementation, a Bidirectional LSTM model has been developed. The RMSprop optimizer is used. The cost function used for the compilation is the mean absolute error function. Finally, to prevent the model from overfitting, early stopping is being used.

The model has been trained with random hyperparameters. To be more precise, 100 different models are generated with different parameters and the model that minimizes the loss is selected for the testing stage. Also, hyperparameters are being assigned from a specified range.

From the training and testing set, the initial hex addresses are converted to decimal values in order to be easier to compare them. After that, the data is being normalized for the acceleration of the training of the model. From a variety of scalers, the Robust scaler is selected since using this scaler the generated models have smaller loss values.

ECE 447 NEURO-FUZZY COMPUTING 
