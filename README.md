# Fashion-MNIST CNN Image Classification

A deep learning project that uses a Convolutional Neural Network (CNN)
to classify clothing images from the Fashion-MNIST dataset.

## Project Overview

This project demonstrates an end-to-end image classification workflow
using TensorFlow and Keras.

The project includes:

- Exploratory data analysis
- Fashion-MNIST dataset visualization
- Image preprocessing
- CNN model development
- Baseline CNN training
- Data augmentation
- Batch normalization
- Dropout regularization
- Model evaluation
- Confusion matrix analysis
- Classification report
- Misclassified image analysis
- Comparison of baseline and improved CNN models

## Dataset

The Fashion-MNIST dataset contains:

- 60,000 training images
- 10,000 test images
- Image size: 28 × 28 pixels
- Grayscale images
- 10 clothing categories

The dataset is loaded automatically using TensorFlow/Keras.

## Classes

The ten classes are:

1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

## Models

### Baseline CNN

The baseline CNN uses convolutional layers, max pooling,
and fully connected layers.

Test accuracy:

**87.13%**

### Improved CNN

The second model introduces:

- Data augmentation
- Batch normalization
- Dropout
- Additional convolutional layers

Test accuracy:

**84.34%**

Interestingly, the improved CNN performed worse than the baseline model.
This demonstrates that increasing model complexity and adding
regularization does not always improve performance.

## Results

The baseline CNN achieved the best test performance in this experiment.

The confusion matrix and misclassified images show that the model
performs well on visually distinctive categories such as sneakers,
sandals, bags, and trousers.

The model has more difficulty distinguishing visually similar
upper-body clothing categories such as shirts, pullovers, coats,
and T-shirts.

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
