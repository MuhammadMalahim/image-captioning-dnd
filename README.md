# Image Captioning

This repository contains a project focused on building an image captioning model using an Encoder-Decoder architecture with Attention. The goal is to train a custom model and compare its performance against a pre-trained model on the Flickr8k dataset.

## Project Overview

The notebook walks through:

- Downloading and preprocessing the Flickr8k dataset  
- Tokenization and vocabulary size management  
- Designing and implementing an Encoder-Decoder + Attention model  
- Training a custom captioning model from scratch  
- Using a pre-trained model for comparison  
- Visualizing attention maps to understand model focus  
- Evaluating model performance using BLEU scores and qualitative caption comparisons  

## Files

- `Image_Captioning.ipynb`: The main Jupyter notebook containing the full pipeline, from preprocessing and model building to evaluation and visualization.

## Technologies Used

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- PyTorch
- NLTK for BLEU score calculation  
- Jupyter Notebook  

## Highlights

- Utilizes the Flickr8k dataset with 8000 images and 40,000 captions  
- Implements an Encoder-Decoder architecture with Attention  
- Fine-tunes a pre-trained CNN (e.g., ResNet) as the encoder  
- Visualizes attention over image regions for generated captions  
- Evaluates model with BLEU scores using all 5 ground truth captions per image  
- Compares the performance of a custom model to a pre-trained baseline  

