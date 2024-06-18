# MNIST Handwritten Digit Recogniser

This project contains the steps to build and train a digit recognition model using the MNIST dataset. It includes data loading, pre processing,
building and training the model, as well as evaluating the model. 5-fold cross validation is used to improve the model's performance.

## Requirements

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn

Install using: `pip install tensorflow keras numpy matplotlib scikit-learn`
Or using pipfile: `pipenv install` or `pipenv sync`

## Results

There is a mean accuracy of **98.96%** on the training data.

The model with the best performance on the test data has an accuracy of **99.18%**.
