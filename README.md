# Image Classification with CNNs

## Overview

This repository contains files related to image classification using Convolutional Neural Networks (CNNs) with Transfer Learning (TL) techniques. The primary focus is on classifying images of ornamental plants.

## Transfer_Learning

This directory contains Transfer Learning (TL) files for all three models used in the project.

## Fine_Tuning

This directory contains the Fine Tuning files for all three models.


## Dataset

The dataset used for this project is Ornamental Plants.
It is uploaded in this Google Drive: https://drive.google.com/drive/folders/1jvnHGOoIyv3TmSX4RW1awxsc4qmnNK6l?usp=sharing

### Categories

1. Damask Rose
2. Echeveria Flower
3. Mirabilis Jalapa
4. Rain Lily
5. Zinnia Elegans

## Models

The images from the dataset are used to train the following pre-trained CNN models using Transfer Learning and Fine-Tuning:

1. **Model-1:** InceptionResNetV2
2. **Model-2:** EfficientNetV2B0
3. **Model-3:** ConvNeXtTiny

## Ensemble Model

An ensemble model(ensemble123.ipynb) is generated using the prediction results of the best-performing Fine-Tuned models.
