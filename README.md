# Multilayer Neural Networks: Analysis of Depth, Width, and Activation Functions

## 📌 Overview

This project presents a structured tutorial and experimental analysis of multilayer perceptrons (MLPs), focusing on how architectural choices—specifically **network depth**, **network width**, and **activation functions**—influence model performance.

Using controlled experiments on non-linear datasets, the project demonstrates how these design decisions affect **learning behaviour**, **decision boundaries**, and **generalisation ability**. The goal is to provide both theoretical understanding and practical insights that can guide effective neural network design.

---

## 🎯 Objectives

* Analyse how increasing **depth** impacts hierarchical feature learning
* Evaluate the effect of **width** on model capacity and flexibility
* Compare **activation functions** (Sigmoid vs ReLU) in terms of training behaviour
* Understand **underfitting, overfitting, and generalisation**
* Provide practical guidelines for designing effective MLP architectures

---

## 📊 Key Findings

* Increasing **depth** improves the ability to learn complex representations, but shows diminishing returns beyond a certain point
* Increasing **width** enhances flexibility but does not always lead to significant performance gains
* **ReLU activation** enables faster convergence and more stable training compared to sigmoid
* Model performance is strongly dependent on **dataset complexity**, not just architecture
* A balance between **model capacity and generalisation** is essential for optimal results

---

## 📁 Repository Structure

```
mlp-depth-width-analysis/
│
├── notebook/
│   └── mlp_analysis.ipynb        # Main experiment notebook
│
├── images/
│   └── decision_boundaries.png   # Generated plots (optional)
│
├── tutorial.pdf                 # Final tutorial submission
├── requirements.txt             # Dependencies
├── README.md                    # Project documentation
└── LICENSE                      # Usage license
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/manichitumala/mlp-depth-width-analysis.git
cd mlp-depth-width-analysis
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the notebook

```bash
jupyter notebook notebook/mlp_analysis.ipynb
```

---

## 🧪 Experiments Included

The Jupyter Notebook contains:

### 🔹 Dataset

* Synthetic non-linear dataset (e.g., spiral / moons)
* Data normalisation and train-test split (80:20)

### 🔹 Model Experiments

* Depth comparison (1, 2, 3 hidden layers)
* Width comparison (4, 16, 32 neurons per layer)
* Activation function comparison:

  * Sigmoid
  * ReLU

### 🔹 Visualisations

* Decision boundary plots
* Model behaviour comparisons
* Performance evaluation across configurations

---

## 🧠 Key Concepts Demonstrated

* Neural network architecture design
* Effect of depth vs width on model capacity
* Activation function impact on gradient flow
* Overfitting vs underfitting
* Importance of dataset complexity

---

## ♿ Accessibility

* Plots include clear axis labels and readable font sizes
* Visualisations use high-contrast, interpretable colour schemes
* Code is structured and commented for clarity
* Notebook is organised for step-by-step understanding

---

## 📚 References

* Goodfellow, I., Bengio, Y., & Courville, A. (2016). *Deep Learning*. MIT Press
* Bishop, C. M. (2006). *Pattern Recognition and Machine Learning*. Springer
* Nielsen, M. A. (2015). *Neural Networks and Deep Learning*
  http://neuralnetworksanddeeplearning.com/
* Stanford University – CS231n
  https://cs231n.stanford.edu/
* Scikit-learn Documentation
  https://scikit-learn.org/

---

## 📜 License

This project is licensed under the **MIT License**.
You are free to use, modify, and distribute this work with proper attribution.

---

## 🔗 GitHub Repository

https://github.com/manichitumala/mlp-depth-width-analysis.git
