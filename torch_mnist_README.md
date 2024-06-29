# MNIST Handwritten Digit Recognition: Model Testing and Visualization

## Description

This Jupyter notebook demonstrates the testing and visualization of a simple neural network model trained on the MNIST handwritten digit dataset. The notebook includes the following key components:

1. **Model Architecture**: A simple neural network (SimpleNN) with fully connected layers is defined to classify handwritten digits.

2. **Data Loading**: The MNIST test dataset is loaded using PyTorch's datasets and DataLoader utilities.

3. **Model Loading**: A pre-trained model is loaded from a file ('mnist_model.pth').

4. **Testing Functions**:
   - `test_and_visualize()`: This function tests the model on a specified number of random images from the test set and visualizes the results, showing both the model's predictions and the true labels.
   - `test_on_entire_set()`: This function evaluates the model's performance on the entire test dataset and reports the overall accuracy.

5. **Visualization**: Matplotlib is used to display sample images along with their predicted and true labels.

6. **Device Configuration**: The notebook checks for MPS (Metal Performance Shaders) availability for Mac users with Apple Silicon, otherwise defaults to CPU.

This notebook serves as a practical example of how to load a trained PyTorch model, test its performance, and visualize its predictions on a classic computer vision dataset. It's an excellent starting point for understanding model evaluation and result visualization in machine learning projects.

To use this notebook:
1. Ensure you have the required libraries installed (PyTorch, torchvision, matplotlib).
2. Make sure the trained model file 'mnist_model.pth' is in the same directory as this notebook.
3. Run the cells in order to see the model's performance and visualize its predictions.
