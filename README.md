# CNN Model with Data Augmentation

This repository contains an implementation of a Convolutional Neural Network (CNN) model for image classification, utilizing data augmentation to improve model performance by artificially increasing the dataset size. The augmentation techniques used include rotation, width and height shifts, shearing, zooming, and horizontal flipping.

## Overview

In deep learning, especially in image classification tasks, a large and diverse dataset is essential for training a robust model. Data augmentation is a technique to artificially increase the size of a dataset by applying random transformations to the images. This repository utilizes the `ImageDataGenerator` class from TensorFlow/Keras to perform real-time augmentations on images during training, enhancing model generalization by providing a more diverse range of images.

## Features

- **Data Augmentation**: Implements various image transformation techniques, such as:
  - Rotation within a range of degrees
  - Shifting of images horizontally and vertically
  - Shearing and zooming of images
  - Horizontal flipping of images
- **Preview of Augmented Images**: Generates and saves augmented images for visualization in a specified directory.
- **Batch Processing**: The augmentation process occurs in batches, allowing for efficient handling of large datasets.

## Prerequisites

Before running the code, ensure the following Python libraries are installed:

- TensorFlow
- Keras
- NumPy

## Usage

- **Prepare Images**: Place the images you want to augment in the project directory.
- **Run Data Augmentation**: The script uses the `ImageDataGenerator` class to apply transformations like rotation, shifting, shearing, zooming, and flipping.
- **Preview Augmented Images**: The augmented images are saved in a directory (e.g., `preview`) for you to visualize.
- **File Naming**: Augmented images are saved with a prefix added to the original filenames to easily distinguish them from the original images.

## Acknowledgements

- **TensorFlow and Keras** for providing powerful tools for image augmentation and deep learning.


