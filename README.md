## Neural Networks - E-tivity 2

## Overview
This repository contains the code and documentation for E-tivity 2: Neural Networks, which explores the implementation of an artificial neural network (ANN) for classification tasks. The project covers manual perceptron implementation, gradient descent optimization, and Scikit-learn-based neural networks.

## Features
- Perceptron Implementation: Manually coded perceptron with a sigmoid activation function.
- Gradient Descent Optimization: Custom loss function and weight updates.
- Scikit-learn MLP: Utilizes a multi-layer perceptron (MLP) for classification.
- Model Fitting Challenge: Feature engineering applied to a challenging dataset.

## Repository Structure

Neural-Networks
      - README.md                   # Project Documentation (this file)
      - Etivity2_NeuralNetworks_23233729.ipynb  # Jupyter Notebook with full implementation
      - t4_data.csv                 # Dataset for model fitting challenge
      - Figures (Diagrams & Plots)
      - perceptron.png             # Perceptron structure visualization
      - perceptron_xy.png          # Perceptron dataset visualization
      - ann_2layers.png            # ANN model architecture

## Installation & Setup
1. Clone the Repository
        git clone https://github.com/yourusername/Neural-Networks.git
        cd Neural-Networks
2. Install Dependencies
         pip install numpy matplotlib scikit-learn
3. Run the Jupyter Notebook
   Launch Jupyter Notebook and open the provided .ipynb file:
         jupyter notebook Etivity2_NeuralNetworks_23233729.ipynb
## Implementation Details

Task 1: Manual Perceptron Implementation
   - Created a single-node Perceptron with a sigmoid activation function.
   - Initialized the Perceptron with random weights and bias.
   - Developed a group prediction function.
   - Evaluated accuracy and visualized the group classification.
Task 2: Gradient Descent Optimization
   - Implemented a loss function (sum of squared errors).
   - Created a gradient descent function for weight updates.
   - Fitted the model until achieving a satisfactory performance.
   - Evaluated final model accuracy and plotted predictions.

Task 3: Scikit-learn MLP Implementation
   - Split dataset into training and testing sets.
   - Defined and trained a multi-layer perceptron (MLP) model.
   - Printed the mean accuracy of the trained model.
   - Plotted model predictions for visual evaluation.

Task 4: Model Fitting Challenge
   - Applied feature engineering techniques to improve model performance.
   - Optimized the ANN structure for handling complex datasets.

## Example Output
      Model: Scikit-learn MLP
      Training Accuracy: 95%
      Testing Accuracy: 91%
      Loss Reduction: Achieved optimal convergence

## Key Learnings
   - Developed a strong foundation in neural network architectures.
   - Implemented a perceptron from scratch using NumPy.
   - Improved model performance using gradient descent optimization.
   - Learned to leverage Scikit-learn’s MLP for rapid ANN deployment.

##  Contributing
   - Fork the repository.
   - Create a new branch (feature-xyz).
   - Commit and push changes.
   - Open a Pull Request.

## License
This project is open-source under the MIT License.

