# Image Caption Generator

## Overview
This project implements an Image Caption Generator using deep learning. It trains a model to generate descriptive captions for images using a combination of a CNN (Convolutional Neural Network) for feature extraction and an RNN (Recurrent Neural Network) for sequence generation.

## Features
- Uses a pre-trained CNN model (e.g., VGG16, ResNet) for feature extraction.
- Implements an LSTM-based RNN for caption generation.
- Trains on an image-caption dataset.
- Generates captions for new images.

## Requirements
To run this notebook, install the following dependencies:
```bash
pip install tensorflow keras numpy pandas matplotlib
```

## Usage
1. Open and run `image-caption-generator.ipynb` in Jupyter Notebook.
2. The dataset will be loaded and preprocessed.
3. The model will be trained and evaluated.
4. You can generate captions for test images.

## Dataset
The notebook likely uses an image-caption dataset such as **Flickr8k, Flickr30k, or MS COCO**. Ensure you have the dataset in the correct directory.

## Results
Once trained, the model generates captions describing the content of images. Example output:
```
Input Image: (image of a dog running)
Generated Caption: "A brown dog running through the grass."
```

## Authors
- itisha choudhary

## License
This project is licensed under the MIT License.

