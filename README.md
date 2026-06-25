# Image Caption Generator

## Overview

Image Caption Generator is a Deep Learning project that automatically generates meaningful textual descriptions for images. The model combines Computer Vision and Natural Language Processing techniques by extracting visual features from images and generating captions word by word.

## Features

* Automatic image caption generation
* Image feature extraction using a pre-trained CNN model
* Sequence generation using Deep Learning
* Caption prediction for unseen images
* Performance evaluation using BLEU Score

## Dataset

The project uses the Flickr8k dataset, which contains:

* 8,000 images
* Multiple human-written captions for each image
* Diverse real-world scenes and objects

## Project Workflow

1. Load and preprocess image-caption data
2. Extract image features using a pre-trained CNN model
3. Clean and tokenize captions
4. Create vocabulary and sequences
5. Train the caption generation model
6. Generate captions for new images
7. Evaluate model performance using BLEU Score

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* NLTK
* Matplotlib
* Pickle

## Model Architecture

* Encoder: Pre-trained CNN for image feature extraction
* Decoder: LSTM-based sequence generation network
* Embedding Layer for word representation
* Dense Layers for next-word prediction

## Results

The model successfully generates descriptive captions for images by learning relationships between visual features and textual descriptions.

