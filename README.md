# Wine-Quality-Dataset
This notebook explores the prediction of wine alcohol levels using machine learning techniques, focusing on using the PyCaret library and a vanilla neural network implemented with TensorFlow's Keras API. The dataset employed for this analysis includes various features describing different attributes of wines, with the target variable being the alcohol content. This was a regression problem.

Using PyCaret, the highest performing model was the XGBoost model, with mean absolute error (MAE) of 0.2339, mean squared error (MSE) of 0.1152, and an R2 score of 0.9244. The density feature emerged as the most significant predictor. 

The neural network architecture comprised an input layer, followed by a layer with 128 neurons and ReLU activation, followed by a dropout layer with a 50% dropout rate. Subsequent layers included a dense layer with 64 neurons, a layer with 32 neurons, both using ReLU activation, and a final layer with one neuron and linear activation. The neural network achieved a MAE of 0.265 and an impressive R2 score of 0.91 after 100 epochs of training using the Adam optimizer and MSE loss function. The results suggest that both XGBoost and neural networks can effectively predict wine alcohol levels.

Please watch the video below.

[![Watch the video](https://img.youtube.com/vi/M5kVLx-cCO4/maxresdefault.jpg)](https://www.youtube.com/watch?v=M5kVLx-cCO4)
