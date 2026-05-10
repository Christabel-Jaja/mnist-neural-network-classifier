# MNIST Handwritten Digit Classifier

A neural network built with PyTorch that classifies handwritten digits from the MNIST dataset.

## Results
- **Test Accuracy: 96.98%** on 10,000 test images

## Model Architecture
- Input layer: 784 neurons (28x28 pixels)
- Hidden layer 1: 256 neurons (ReLU)
- Hidden layer 2: 128 neurons (ReLU)
- Hidden layer 3: 64 neurons (ReLU)
- Output layer: 10 neurons (LogSoftmax)

## Technologies
- Python
- PyTorch
- NumPy
- Matplotlib

## Dataset
MNIST — 60,000 training images and 10,000 test images of handwritten digits (0-9).

## How to Run
1. Install dependencies: `pip install torch torchvision numpy matplotlib`
2. Open `MNIST.ipynb` in Jupyter Notebook
3. Run all cells
