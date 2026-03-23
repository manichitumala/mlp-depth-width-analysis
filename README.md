# Multilayer Perceptron Analysis: Depth, Width and Activation Functions

## Overview

This project investigates how key architectural choices in Multilayer Perceptrons (MLPs) influence their ability to learn complex, non-linear patterns.

The tutorial focuses on three main aspects:

* **Network Depth** (number of hidden layers)
* **Network Width** (number of neurons per layer)
* **Activation Functions** (Sigmoid, Tanh, ReLU)

In addition, the project demonstrates **overfitting behaviour** in high-capacity neural networks.

---

## Dataset

A **synthetic spiral dataset** is used for experimentation. This dataset is highly non-linearly separable, making it ideal for analysing how neural networks learn complex decision boundaries.

The dataset is generated programmatically within the notebook and split into training and testing sets (80:20).

---

## Experiments

The notebook includes the following experiments:

### 1. Effect of Depth

* Models with 1, 2, and 3 hidden layers are compared
* Demonstrates how deeper networks learn more complex representations

### 2. Effect of Width

* Models with 4, 16, and 64 neurons per layer are evaluated
* Shows how increasing capacity improves performance but may lead to overfitting

### 3. Activation Functions

* Comparison of:

  * Sigmoid (`logistic`)
  * Tanh
  * ReLU
* Highlights the impact of activation functions on learning efficiency

### 4. Overfitting Demonstration

* A large model (3 layers × 128 neurons) is used
* Shows how excessive model complexity leads to poor generalisation

---

## Visualisation

The project includes decision boundary plots for all experiments. These visualisations help illustrate:

* Underfitting in simple models
* Improved learning with increased depth and width
* Differences between activation functions
* Overfitting in high-capacity models

---

## How to Run

### 1. Install dependencies

```bash
pip install numpy matplotlib scikit-learn
```

### 2. Run the notebook

Open:

```
ML neural networks.ipynb
```

Run all cells to reproduce results and visualisations.

---

## Key Insights

* Deeper networks can learn hierarchical and complex patterns more effectively
* Wider networks increase representational capacity but may overfit
* ReLU activation enables faster and more stable training compared to Sigmoid and Tanh
* Overfitting occurs when model complexity is too high relative to the data

---

## Repository Structure

```
mlp-depth-width-analysis/
│
├── ML neural networks.ipynb   # Main implementation and experiments
├── README.md                  # Project documentation
├── LICENSE                    # Usage license
```

---

## Accessibility

All visualisations use colourblind-friendly colour maps to ensure readability and accessibility.

---

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute this work with proper attribution.

