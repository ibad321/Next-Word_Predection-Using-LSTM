# LSTM Next Word Prediction

This repository contains code for training a Long Short-Term Memory (LSTM) neural network model to predict the next word in a sequence of text. The model is trained on the text data from "The Adventures of Sherlock Holmes" taken from the Kaggle dataset [the-adventures-of-sherlock-holmes/The Adventures of Sherlock Holmes.txt](https://www.kaggle.com/)

## Dataset
The dataset consists of the text from "The Adventures of Sherlock Holmes" by Sir Arthur Conan Doyle. It is used for training the LSTM model to predict the next word in a sequence of words.

## Model Training
The LSTM model is implemented using TensorFlow/Keras. The text data is preprocessed and tokenized before being fed into the model. The model is trained on the dataset to learn the patterns in the text and predict the next word based on the input sequence.

## Usage
To use the code in this repository, follow these steps:

1. Download the dataset from Kaggle [the-adventures-of-sherlock-holmes/The Adventures of Sherlock Holmes.txt](https://www.kaggle.com/)
2. Preprocess and tokenize the text data.
3. Train the LSTM model on the preprocessed data.
4. Use the trained model to predict the next word in a sequence of text.

## Requirements
- Python 3.x
- TensorFlow
- Keras
- NumPy
- Pandas

## Credits
- Dataset: [the-adventures-of-sherlock-holmes/The Adventures of Sherlock Holmes.txt](https://www.kaggle.com/)
- Inspired by similar projects and tutorials on LSTM text generation.

Feel free to contribute to this project by forking and submitting a pull request. If you have any questions or suggestions, please open an issue.
