# Machine-Learning-Course

# Assignment 1: Recognize a Digit using TensorFlow

This project is part of the Machine Learning course assignment.

## Dataset
MNIST dataset containing 70,000 grayscale handwritten digits (0–9), each 28x28 pixels.

## Model
A Convolutional Neural Network (CNN) built using TensorFlow/Keras.

**Layers:**
- Conv2D → MaxPooling2D → Conv2D → MaxPooling2D → Flatten → Dense → Dense(Softmax)

## Requirements
- Python 3.x
- TensorFlow
- NumPy
- Matplotlib

## How to Run
1. Open `Assignment1.ipynb` in Google Colab or Jupyter Notebook.
2. Run all cells.
3. The model will train for 5 epochs and output test accuracy.

## Output
- Model summary
- Training accuracy & loss
- Test accuracy
- Example predictions
