# Fashion MNIST Classification with TensorFlow

This project implements a Convolutional Neural Network (CNN) to classify images from the Fashion MNIST dataset using TensorFlow and Keras. The model is designed to achieve high accuracy while incorporating various best practices and optimization techniques.

## Key Features

- Efficient data pipeline using TensorFlow's `tf.data` API
- Custom model architecture using the Functional API
- Data augmentation for improved generalization
- Mixed precision training for faster computation
- Custom learning rate schedule with adjustable rates
- Test-time augmentation for more robust predictions
- Comprehensive model evaluation and visualization

## Model Architecture

The CNN model includes:
- Multiple convolutional layers with batch normalization and max pooling
- Dropout for regularization
- Dense layers with L2 regularization

## Training Process

The training process includes:
- Custom callbacks for learning rate adjustment
- Early stopping to prevent overfitting
- Model checkpointing to save the best weights
- TensorBoard integration for monitoring training progress

## Evaluation and Visualization

The notebook provides:
- Training history plots (accuracy and loss)
- Confusion matrix visualization
- Classification report with precision, recall, and F1-score
- Grid of sample predictions with confidence scores

## Requirements

- TensorFlow 2.x
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Usage

1. Clone the repository
2. Open the `fashion_mnist_classification.ipynb` notebook in Jupyter or JupyterLab
3. Run the cells sequentially to train and evaluate the model

## Results

The model achieves high accuracy on the Fashion MNIST dataset, with detailed performance metrics provided in the notebook.

Feel free to experiment with the hyperparameters and model architecture to further improve the results!
