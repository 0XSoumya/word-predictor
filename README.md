# Word Prediction using LSTM

This project involves creating a word prediction model using Long Short-Term Memory (LSTM) neural networks. The training dataset is composed of text from the complete works of Sherlock Holmes, downloaded from The Gutenberg Project.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Usage](#usage)
- [Results](#results)
- [Requirements](#requirements)
- [Installation](#installation)
- [License](#license)

## Introduction
The goal of this project is to build a word prediction model that can predict the next word in a sequence of text. The model is trained on the text from the Sherlock Holmes series by Sir Arthur Conan Doyle.

## Dataset
The training dataset consists of the text from the complete works of Sherlock Holmes, obtained from [The Gutenberg Project](https://www.gutenberg.org/).

## Model Architecture
We use an LSTM neural network for this task. LSTMs are a type of recurrent neural network (RNN) that are well-suited for sequence prediction tasks.

## Training
The training process involves the following steps:
1. Preprocessing the text data.
2. Creating sequences of text.
3. Encoding the sequences.
4. Defining the LSTM model.
5. Training the model.

## Usage
To use the model for word prediction, you can input a sequence of words, and the model will predict the next word in the sequence.

## Results
The model achieves a good level of accuracy in predicting the next word in a sequence. The performance can be further improved by training on a larger dataset or using more complex models.

## Requirements
- Python 3.6+
- TensorFlow
- Keras
- NumPy
- Pandas

## Installation
1. Clone the repository: https://github.com/0XSoumya/word-predictor.git
