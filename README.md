# Vision-Transformer-for-Galaxy-Classifier
Brown University Visual Computing Lab Starter Project

## Background and Motivation

Transformers have increasingly become the mainstream Natural Language Processing Model due to its advantages over CNN: 1. suitable for Parallel Processing with GPUs therefore faster training  2. More intuitive and better interpretability

With the 2021 paper AN IMAGE IS WORTH 16X16 WORDS: TRANSFORMERS FOR IMAGE RECOGNITION AT SCALE, visual transformers have been shown to perform better than state-of-the-art CNNs. In this project, I will implement the visual transformer model using Python Tensorflow framework and perform image classification on galaxy zoo image dataset. 


## Dataset
The dataset for this project is the Galaxy 10 dataset (see https://astronn.readthedocs.io/en/latest/galaxy10sdss.html) which contains 21785 images of size 69 x 69 taken from the SDSS (Sloan Digital Sky Survey). The images are classified manually by volunteers in a crowd source project and are divided into 10 classes: 

├── Class 0 (3461 images): Disk, Face-on, No Spiral
├── Class 1 (6997 images): Smooth, Completely round
├── Class 2 (6292 images): Smooth, in-between round
├── Class 3 (394 images): Smooth, Cigar shaped
├── Class 4 (1534 images): Disk, Edge-on, Rounded Bulge
├── Class 5 (17 images): Disk, Edge-on, Boxy Bulge
├── Class 6 (589 images): Disk, Edge-on, No Bulge
├── Class 7 (1121 images): Disk, Face-on, Tight Spiral
├── Class 8 (906 images): Disk, Face-on, Medium Spiral
└── Class 9 (519 images): Disk, Face-on, Loose Spiral
Galaxy10 is meant to be an alternative to MNIST or Cifar10 as a deep learning toy dataset for astronomers.

## Visual Transformer Model
Extensive explanations and comments for code will be provided in the ipynb file. 

## Credit goes to:
SDSS (Sloan Digital Sky Survey)
Alexey Dosovitskiy: author of vision transformer paper


