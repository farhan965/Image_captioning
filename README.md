
 # Image Caption Generator

## Goal 

The Objective of this project is to build a working model of image caption generator by using CNN (Conventional Neural networks) with LSTM (Long short-term memory). Image features will be extracted and then we feed to the LSTM model for generating image captions. 
In simple words, goal is to build a model which takes image as input and outputs its caption.


## Process Flow:

Steps followed for the algorithm implementaton
1. Data Collection
2. Data Cleaning
3. Data pre processing
4. Feature Extraction
6. Model Architecture
7. Model Training
8. Model Evaluation

## Model Implementation:

The LSTM takes the image feature vector as input and generates a sequence of words as output. The input to the LSTM is typically pre-processed using an embedding layer, and the output is fed through a fully connected layer to generate the next word in the sequence

## Challenges/Limitations:

1. Images used for testing must be relevant to those used for training the model.
2. As the size of the training dataset increases, the run time of the model would increase rapidly.
