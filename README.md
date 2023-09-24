<!-- # Translation model: English to German

## Model Architecture
Encoder-Decoder Model using Bidirectional LSTM

## Dataset
English to German: https://www.manythings.org/anki/deu-eng.zip -->
# Neural Machine Translation using PyTorch

This repository contains code snippets for a Neural Machine Translation (NMT) system implemented using PyTorch. 

## Overview

The code snippets are organized into different sections, each representing a specific part of the NMT system. Here's a brief overview of what each section does:

### Encoder and Decoder
Building blocks of the Encoder and Decoder is bidirectional LSTM.<br>
The encoder processes the source language input, while the decoder generates the target language output.

### Data Preprocessing

The initial code snippets focus on data preprocessing. They include functions to normalize and prepare text data, create vocabularies, and encode the data for training.

### Dataset and DataLoader

Define a custom dataset and a data loader using PyTorch's DataLoader class. This is crucial for efficiently feeding data to the model during training.


### Training

The training section includes code for training the NMT model. It covers loss computation, backpropagation, and optimization using SGD (Stochastic Gradient Descent).

### Translation

There is a translation function that takes an input sequence in the source language and generates the corresponding translation in the target language. This function uses the trained encoder and decoder models.