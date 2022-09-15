# Introduction
In this project, I will build a deep neural network that functions as part of an end-to-end machine translation pipeline. The completed pipeline will accept English text as input and return the French translation.

## Install
- Python 3
- NumPy
- TensorFlow 1.x
- Keras 2.x

## Dataset
The most common datasets used for machine translation are from [WMT](http://www.statmt.org/). However, that will take a long time to train a neural network on. I'll be using a dataset we created for this project that contains a small vocabulary. 

## Text Preprocessing
1. Tokenize the words into ids
2. Add padding to make all the sequences the same length.

## Models
- Model 1 is a simple RNN - **`77.10% Accuracy`**
- Model 2 is a RNN with Embedding - **`93.07% Accuracy`**
- Model 3 is a Bidirectional RNN - **`76.16% Accuracy`**
- Model 4 is an Encoder-Decoder RNN - **`45.39% Accuracy`**
- Model 5 is an Encoder-Decoder Bidirectional RNN with Embedding - **`97.28% Accuracy`**

