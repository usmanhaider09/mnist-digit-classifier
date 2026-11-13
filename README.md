# MNIST Digit Classifier

A beginner-friendly practice project that classifies handwritten digits (0-9) from the MNIST dataset using a neural network built with TensorFlow and Keras.

## What it does
- Loads the MNIST dataset (60,000 training and 10,000 test images, 28x28 grayscale)
- Flattens the images and builds a `Sequential` model with `Dense` layers
- Trains with `sparse_categorical_crossentropy` loss and the Adam optimizer
- Evaluates accuracy on the test set and visualizes images with Matplotlib

## Tech stack
Python, TensorFlow/Keras, scikit-learn, Matplotlib

## Setup
```bash
pip install -r requirements.txt
```

## Run
Open the notebook and run all cells, or run the script:
```bash
python main.py
```