# Digit_Classifier_ANN_mnist

# MNIST Digit Classification using ANN
This project builds and evaluates an Artificial Neural Network (ANN) for classifying handwritten digits from the MNIST dataset. Multiple activation functions, optimizers, and training epochs were tested to compare their impact on accuracy and loss.

## Final Experiment Results – ANN on MNIST

| Activation | Epochs | Optimizer | Extra Hidden Layer | Accuracy (%) | Loss   |
|------------|--------|-----------|---------------------|--------------|--------|
| ReLU       | 5      | Adam      | No                  | 97.28        | 0.085  |
| ReLU       | 5      | Adam      | Yes                 | 97.63        | 0.088  |
| Tanh       | 5      | Adam      | No                  | 97.28        | 0.090  |
| Tanh       | 10     | Adam      | No                  | 97.54        | 0.082  |
| ReLU       | 10     | Adam      | No                  | 97.62        | 0.084  |
| ReLU       | 10     | SGD       | No                  | 95.16        | 0.175  |
| Tanh       | 10     | SGD       | No                  | 93.75        | 0.220  |

