# Sequence Processing with Recurrent Neural Networks

## Overview

This repository explores the implementation of Sequence Processing using Recurrent Neural Networks (RNNs) with a focus on Part-of-Speech (POS) tagging. The objective is to construct an RNN that annotates each word in a sentence with a linguistically informative marker, such as a POS tag.

## Background
In the realm of natural language processing, the need for machinery capable of processing sequences of words has led to the prominence of Recurrent Neural Networks (RNNs). Unlike standard fully-connected networks, RNNs operate on sequences of vectors, making them suitable for tasks involving larger linguistic units like phrases, sentences, and dialogues.

The project takes a gradual approach, starting with an understanding of RNNs, moving on to building a Simple Recurrent Network (SRN) from scratch, and ultimately applying the SRN for POS tagging.
## Key Features

- Define SRN for POS Tagging: Create an SRN for POS tagging with appropriate input and output sizes, hidden layer activation as "tanh," and suitable activation and loss functions.
- Training the SRN: Instantiate an optimizer, train the network for a specified number of epochs, and measure/print loss and accuracy metrics for both training and validation sets.
- Visualization: Plot loss and accuracy curves for training and validation sets to visualize the training progress

## Requirements
- torch ver=2.1.0+cu118
- numpy ver=1.23.5
- spacy ver=3.6.1
- pickle

## Installation
Clone the repository to your local machine:
git clone https://github.com/aalexa201222/Sequence-Processing-with-Recurrent-Neural-Networks.git

## Contributors
https://github.com/aalexa201222/Sequence-Processing-with-Recurrent-Neural-Networks
[Andreas Alexandrou](https://www.linkedin.com/in/andreas-alexandrou-056528242) <br />
Sotiris Zenios
