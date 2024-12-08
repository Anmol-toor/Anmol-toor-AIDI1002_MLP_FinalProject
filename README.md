# Transformer-Based Sigmoid Approximation

This repository implements a Transformer-based neural network inspired by the principles outlined in [Large-Scale Legal Text Classification Using Transformers](https://paperswithcode.com/paper/large-scale-legal-text-classification-using). The project adapts the Transformer architecture to approximate the sigmoid function, focusing on analyzing its predictions and training behavior.

## Features
- Implementation of a Transformer model for sequence-to-sequence prediction.
- Visualization of actual and predicted sigmoid values.
- Analysis of training loss and model performance.

## How to Run
1. Clone the repository.
2. Install the following dependencies:
   - Python 3.x
   - Jupyter Notebook
   - PyTorch
   - Matplotlib
   - NumPy
3. Open the `Transformer.ipynb` file in Jupyter Notebook and run the cells sequentially to train the model and visualize results.

## Results
The model's predictions deviate significantly from the actual sigmoid function, highlighting challenges in training Transformers for such tasks.

## Future Work
- Explore alternative architectures and hyperparameter tuning.
- Investigate methods to improve training stability and model generalization.
