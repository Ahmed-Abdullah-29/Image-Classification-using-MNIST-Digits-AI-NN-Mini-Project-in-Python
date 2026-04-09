#  MNIST Digit Classification using Deep Neural Networks

This project implements **handwritten digit classification (0–9)** 
using the **MNIST dataset** and multiple deep learning approaches built with **TensorFlow/Keras**.
It includes both **conceptual exploration** and a **controlled experiment comparing Sigmoid vs Tanh activation functions**.

##  Project Overview

This project is divided into two major parts:

### PART A — Exploratory Deep Learning Concepts
Covers foundational neural network concepts through practical implementation:

- Dense Neural Networks (Fully Connected Layers)
- Overfitting demonstration
- Dropout regularisation
- Early stopping
- Convolutional Neural Networks (CNN)
- Data augmentation techniques

### PART B — Main Assignment (Sigmoid vs Tanh)
Implements a **6-hidden-layer neural network** and compares:
- Sigmoid activation
- Tanh activation
- Tanh with Dropout (0.3)

All models are trained under identical conditions for fair comparison.

## Dataset
- **Dataset:** MNIST (built-in via TensorFlow)
- **Total Images:** 70,000
- **Training:** 60,000
- **Testing:** 10,000
- **Image Size:** 28 × 28 (grayscale)
- **Classes:** Digits 0–9

## Model Architecture (Assignment Requirement)
## ⚙️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

##  Experiments Conducted

### 1. Baseline Model
- Simple Dense network with 1 hidden layer
- Used for performance comparison

### 2. Overfitting Demonstration
- Larger model trained for many epochs
- Shows divergence between training and validation performance

### 3. Dropout Regularisation
- Applied Dropout layers (0.5)
- Demonstrates improved generalisation

### 4. CNN with Data Augmentation
- Convolutional model for image-specific learning
- Uses rotation, translation, and zoom
  
## Main Experiment Results

| Model | Test Accuracy |
|------|-------------|
| Sigmoid (6 hidden layers) | ~96.3% |
| Tanh (6 hidden layers) | ~96.9% |
| Tanh + Dropout (0.3) | ~97.2% |


## Key Insights

- **Tanh outperforms Sigmoid** due to zero-centered outputs
- Sigmoid suffers from **vanishing gradient problem**
- **Dropout improves generalisation**
- CNN provides strong performance for image-based tasks
- Learning rate significantly affects convergence

---

## Visual Outputs

The project generates:

- Training & validation curves
- Confusion matrices
- Misclassified image analysis
- Learning rate comparison plots
- Dropout vs non-dropout comparison
- Per-class performance tables
- 
## 📁 Project Structure

## Skills Demonstrated
- Deep Learning (Neural Networks)
- Model Architecture Design
- Activation Function Analysis
- Overfitting & Regularisation Techniques
- Model Evaluation (Precision, Recall, F1-score)
- Confusion Matrix Analysis
- Data Visualisation
- Experimental Comparison (Controlled setup)

## Learning Outcomes
- Understanding of activation functions (Sigmoid vs Tanh)
- Importance of early stopping and dropout
- Impact of learning rate on training
- CNN advantages for image classification
- Interpretation of classification metrics

## Conclusion
- This project demonstrates a complete deep learning workflow from basic models to advanced experimentation.
- The results clearly show that Tanh activation with dropout provides the best performance for this architecture.
