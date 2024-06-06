# Tea Leaf Disease Classification

This repository contains a deep learning project for classifying tea leaf diseases using Convolutional Neural Networks (CNNs) implemented in TensorFlow and Keras.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

The objective of this project is to classify different types of diseases affecting tea leaves using images. The model is trained using a CNN and employs data augmentation techniques to improve generalization.

## Dataset

The dataset should be organized in a directory structure where each subdirectory represents a different class of tea leaf disease.

## Model Architecture

The model is a Convolutional Neural Network (CNN) consisting of several convolutional layers, max-pooling layers, and dense layers. The architecture is designed to handle the complexity of image data and perform classification.

## Installation

To run this project, you'll need to install the required dependencies. Use the following commands to set up your environment:

``sh
pip install matplotlib numpy notebook tensorflow-addons tensorflow-model-optimization tensorflow==2.15.0 keras
pip install --upgrade pip
pip install --upgrade tensorflow
Usage
Load and preprocess the data:
Ensure your dataset is in the correct directory structure as mentioned above.

## Run the training script:
The script will load the dataset, preprocess the images, and train the model.

## Evaluate the model:
After training, the model will be evaluated on the test set, and the results will be visualized.
Results
After training, the model's performance is evaluated on the test set, and the training/validation accuracy and loss are plotted. The model predictions are also visualized to compare with actual labels.

## Contributing
Contributions are welcome! Please fork this repository and submit pull requests for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

