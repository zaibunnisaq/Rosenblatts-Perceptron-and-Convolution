# Rosenblatt's Perceptron from Scratch

## Overview
This project implements **Rosenblatt's Perceptron** from scratch to classify a **synthetic dataset** with two features. The dataset contains **500 samples** labeled based on a **linear decision boundary**. The perceptron algorithm is trained using a step activation function and updates weights only when a misclassification occurs.

## Methodology
1. **Dataset Generation**:
   - A synthetic dataset with 500 samples and two features was created.
   - Labels were assigned based on a linear decision boundary.
   - The dataset was split into **80% training** and **20% testing**.

2. **Perceptron Implementation**:
   - Computes the weighted sum of inputs plus bias.
   - Uses a **step activation function** for classification.
   - Updates weights only when misclassification occurs.

3. **Visualization**:
   - **Scatter Plot**: Displays the two classes in the dataset.
   - **Decision Boundary**: The computed decision boundary is overlaid on the test dataset.

## Performance Analysis
- **Test Accuracy**: **99%**
- The perceptron successfully learned a **linear separation** between the two classes.
- Misclassifications occur in regions where the classes overlap due to the **linear nature** of the perceptron.

## Discussion
- The perceptron efficiently learns a **linear decision boundary**.
- Due to its **linear nature**, it cannot classify **non-linearly separable data**.
- Further improvements can be made using **multi-layer perceptrons** or **non-linear kernels**.

## Author
**Zaib Un Nisa**
