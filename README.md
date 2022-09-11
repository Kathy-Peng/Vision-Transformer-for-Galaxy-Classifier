# Vision-Transformer-for-Galaxy-Classifier
Brown University Visual Computing Lab Starter Project

## Background and Motivation

Transformers have increasingly become the mainstream Natural Language Processing Model due to its advantages over CNN: 1. suitable for Parallel Processing with GPUs therefore faster training  2. More intuitive and better interpretability

With the 2021 paper AN IMAGE IS WORTH 16X16 WORDS: TRANSFORMERS FOR IMAGE RECOGNITION AT SCALE, visual transformers have been shown to perform better than state-of-the-art CNNs. In this project, I will implement the visual transformer model using Python Tensorflow framework and perform image classification on galaxy zoo image dataset. 


## Dataset
The dataset is the Galaxy Zoo dataset from the galaxy challenge eight years ago, with the labels mannually produced by volunteers who classify the galaxy images taken from the SDSS (Sloan Digital Sky Survey). There are 6 possible classes for galaxies: elliptical, clockwise spiral, anticlockwise spiral, edge-on , star/don't know, or merger. The dataset used in this project is given in zip files: train_x.zip, train_y.zip, and test_x.zip. Datasets are too large to be added to github repo and can be accessed here: https://drive.google.com/drive/folders/1IOx5ZplbTnpaZrQSFC5OaLiyPOppDRpL?usp=sharing

## Visual Transformer Model
Extensive explanations and comments for code will be provided in the ipynb file. 

## Credit goes to:
SDSS (Sloan Digital Sky Survey)
Alexey Dosovitskiy: author of vision transformer paper


