# DNN Classifiers and Fast Rates

This repository contains Jupyter Notebooks designed to study the performance of deep neural network (DNN) classifiers under various conditions, with a focus on understanding margin behavior and fast convergence rates. The experiments are conducted using popular datasets such as CIFAR-10, Fashion MNIST, MNIST, and STL-10.

## Contents

The repository includes the following notebooks:

- **CIFAR-10 Experiments**:
  - `cifar10_auto_truck_histogram.ipynb`: Analyzes margin behavior for the "automobile" and "truck" classes.
  - `cifar10_cat_dog_histogram.ipynb`: Studies margin behavior for the "cat" and "dog" classes.
  - `cifar10_histogram_logistic_loss.ipynb`: Explores histograms of classifier outputs trained with logistic loss.
  - `cifar_10_margin.ipynb`: Investigates margin conditions for CIFAR-10.

- **Fashion MNIST Experiments**:
  - `fashion_mnist_tshirt_pullover_histogram.ipynb`: Analyzes margin behavior for the "T-shirt/top" and "Pullover" classes.
  - `fashion_mnist_histogram_logistic_loss.ipynb`: Studies histograms of classifier outputs with logistic loss.
  - `fashion_mnist_margin.ipynb`: Examines margin conditions for Fashion MNIST.

- **Other Datasets**:
  - `mnist_margin.ipynb`: Investigates margin conditions for MNIST.
  - `stl10_margin.ipynb`: Analyzes margin behavior for the STL-10 dataset.

- **Synthetic Data**:
  - `concentric_circles_hard_margin.ipynb`: Studies hard margin conditions using concentric circles data.
  - `concentric_circles_weak_margin.ipynb`: Explores weak margin conditions using concentric circles data.

## Description

This repository aims to empirically evaluate margin conditions and their implications for fast convergence rates in DNN classifiers. The experiments focus on:
1. Investigating classifier outputs for different datasets and loss functions.
2. Visualizing margins using histograms and interpolated samples.
3. Comparing hard and weak margin conditions on specific datasets.

## Getting Started

To run the notebooks, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/StratosFair/DNN_Classifiers_Fast_Rates.git
   cd DNN_Classifiers_Fast_Rates
