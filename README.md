# Captum-Insights-and-Robustness
This repository showcases the usage of Captum, a model interpretability library for PyTorch, along with adversarial attacks and robustness evaluation techniques.

It showcases the usage of Captum for interpreting a pre-trained convolutional neural network model trained on the FashionMNIST dataset and evaluating its robustness against adversarial attacks.

## Features

- **Attributions Visualization:** Visualizes the attributions of features to the model's predictions, providing insights into what parts of the input contribute most to the model's output.
- **Model Understanding:** Offers a deeper understanding of the model's decision-making process through interpretation and visualization of its internal workings.
- **Adversarial Attacks:** Demonstrates the application of FGSM and PGD adversarial attack algorithms to generate perturbed images.
- **Robustness Evaluation:** Evaluates the model's robustness against adversarial attacks by analyzing its performance on perturbed images.

## Usage

To use the project:
1. Ensure you have all the necessary dependencies installed.
2. Run the provided scripts to visualize attributions, apply adversarial attacks, and evaluate model robustness.

## Pre-Trained Model

The project utilizes a pre-trained convolutional neural network model trained on the FashionMNIST dataset, loaded from a pre-trained checkpoint file.

## Adversarial Attacks

- **Fast Gradient Sign Method (FGSM):** Generates adversarial examples by perturbing input images in the direction of the sign of the gradient of the loss function with respect to the input.
- **Projected Gradient Descent (PGD):** Implements an iterative approach to generate adversarial examples while ensuring that perturbations are within a specified epsilon range.

## Contributing

Contributions to this project are welcome! Feel free to open issues or submit pull requests.

