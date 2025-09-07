# ANN-from-scratch--
This is my attempt at creating an artificial neural network from scratch using only NumPy without the help of any NN libraries. This NN has been trained on Fashion MNIST and MNIST datasets.

## 🚀 Features
- Fully connected MLP implementation.
- Train/test split with validation set.
- Adam optimizer for efficient training.
- Accuracy tracking across epochs.
- Misclassified samples visualization.

## 📊 Datasets
### MNIST
- Handwritten digits `0–9`.
- 60,000 training images + 10,000 test images.
- Image size: `28 x 28` grayscale.

### Fashion-MNIST
- 10 classes of Zalando fashion items (e.g., sneakers, coats, bags).
- 60,000 training images + 10,000 test images.
- Image size: `28 x 28` grayscale.

Both datasets are loaded via `keras.datasets`.

