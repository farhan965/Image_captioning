
 # Image Caption Generator

## Goal 

The Objective of this project is to build a working model of image caption generator by using CNN (Conventional Neural networks) with LSTM (Long short-term memory). Image features will be extracted and then we feed to the LSTM model for generating image captions. 
In simple words, goal is to build a model which takes image as input and outputs its caption.


## Process Flow:

Steps followed for the algorithm implementaton
1. Data Collection
2. Data Cleaning
3. Data integration
4. Data Pre-processing of images
5. Data Pre-processing of Captions
6. Data Modelling
7. Model Evaluation

## Model Implementation:

An embedding matrix is created from Glove embeddings and this will directly copied to the weight matrix of the neural network.
The LSTM(Long Short Term Memory) layer is to process the sequence input text data.(partial captions in our case).

## Challenges/Limitations:

1. Images used for testing must be relevant to those used for training the model.
2. As the size of the training dataset increases, the run time of the model would increase rapidly.
