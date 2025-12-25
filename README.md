# Data Augmentation using Keras

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Keras](https://img.shields.io/badge/Keras-Data%20Augmentation-purple)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![Notebook](https://img.shields.io/badge/Made%20with-Jupyter-orange)
![Colab](https://img.shields.io/badge/Run%20on-Google%20Colab-yellow)

This project demonstrates data augmentation techniques used in deep learning to improve the performance and generalization of image classification models.

The implementation is provided in a Jupyter Notebook using Python and TensorFlow/Keras.

---

## Project Overview

Data augmentation artificially increases the size and diversity of a dataset by applying transformations to existing images. This helps models:
- Reduce overfitting
- Improve generalization
- Learn robust visual features

In this notebook, we apply common augmentation techniques such as rotation, flipping, zooming, and shifting on image data.

---

## Techniques Covered

- Image Rescaling
- Random Rotation
- Horizontal & Vertical Flipping
- Width & Height Shifting
- Zooming
- Shearing
- Real-time augmentation using `ImageDataGenerator`

---

## Augmented Images Preview

To make the data augmentation process transparent and easy to understand, I have generated augmented images and pushed them to this GitHub repository.

This allows you to visually compare:
- Original images
- Augmented images (after applying transformations like rotation, flipping, zooming, etc.)

### How to View

- Navigate to [data/original_images/](./Images/Original_Image/) to see the raw input images
- Navigate to [data/augmented_images/](./Images/Augmented_Images/) to see the generated augmented samples

---

## Use Cases

- Image Classification (Cats vs Dogs, CIFAR-10, etc.)
- Small or imbalanced datasets
- Preprocessing pipeline for CNN models
- Academic learning & experimentation
