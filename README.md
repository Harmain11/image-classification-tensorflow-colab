# Image Classification with TensorFlow in Google Colab

## Overview
This notebook provides a step-by-step process for loading, verifying, augmenting, and preparing an image dataset for classification using TensorFlow. It utilizes Google Colab environment with direct integration to Google Drive storage. The notebook handles dataset partitioning and preprocessing for training a neural network.

## Features
- Mount Google Drive to access images
- Validate and verify image file integrity
- Load image dataset with TensorFlow's image_dataset_from_directory
- Partition dataset into training, validation, and testing sets
- Implement data augmentation to enhance training data
- Use TensorFlow preprocessing layers for resizing and rescaling images

## Tech Stack
- Python
- Jupyter Notebook / Google Colab
- TensorFlow (tf.keras)
- Pillow (PIL)
- matplotlib

## How to Use
1. Mount Google Drive and set the path to your image dataset.
2. Run image verification cells to check data integrity.
3. Load and partition your dataset into train, validation, and test subsets.
4. Apply preprocessing and augmentation pipelines.
5. Use the prepared datasets to train your TensorFlow model.

## Status
This notebook is organized and cleaned for GitHub presentation, suitable for further development and adaptation.