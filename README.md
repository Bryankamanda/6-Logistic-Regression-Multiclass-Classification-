

#  Multiclass Logistic Regression – Handwritten Digits Classification

##  Project Overview

This project implements a **Multiclass Logistic Regression model** to classify handwritten digits using the built-in **`digits` dataset from Scikit-learn**.

The dataset contains images of handwritten digits (0–9), and the goal is to correctly predict which digit each image represents. This is a classic **multiclass classification problem** widely used to evaluate machine learning models on image-like structured data.

---

##  Objective

To build and evaluate a machine learning model that:

* Classifies handwritten digits (0–9)
* Handles **multiclass classification using Logistic Regression**
* Learns patterns from pixel-based features
* Evaluates performance using standard classification metrics

---

##  Key Concepts Covered

### 1. Multiclass Logistic Regression

Logistic Regression is extended to handle multiple classes using:

* **One-vs-Rest (OvR)** or
* **Softmax (Multinomial Logistic Regression)**

Each input image is assigned a probability across all digit classes, and the highest probability class is selected as the prediction.

---

### 2. Dataset Used – `digits` (Scikit-learn)

* 1,797 samples
* 8×8 grayscale images
* 64 pixel features per sample
* 10 target classes (digits 0–9)

Each image is flattened into a feature vector for model training.

---

### 3. Feature Representation

Images are converted from 2D pixel grids into:

```
(1797 samples, 64 features)
```

This allows Logistic Regression to process image data as structured numeric input.

---

### 4. Model Training Process

* Load dataset from `sklearn.datasets`
* Normalize/prepare feature matrix
* Split into training and test sets
* Train Logistic Regression classifier
* Predict and evaluate results

---

##  Tools & Libraries Used

* Python 
* NumPy 
* Pandas 
* Matplotlib 
* Scikit-learn 
* Jupyter Notebook 

---

##  Model Evaluation

The model is evaluated using:

* **Accuracy Score**
* **Confusion Matrix**
* Class-wise prediction performance

These metrics help assess how well the model distinguishes between similar-looking digits.

---

##  Key Insights

* Logistic Regression performs surprisingly well on linearly separable digit data
* Some digits may overlap visually (e.g., 3 vs 5, 8 vs 9), making classification harder
* Feature scaling improves convergence and stability
* Multiclass classification can be efficiently handled using scikit-learn’s built-in implementations

---

##  Why This Project Matters 

This project demonstrates:

* Understanding of **multiclass classification problems**
* Ability to preprocess image-like structured data
* Practical use of **Scikit-learn ML workflows**
* Knowledge of model evaluation techniques
* Foundation for deeper computer vision and deep learning work

---

##  Real-World Applications

This type of model is used in:

* OCR (Optical Character Recognition)
* Automated form digit reading
* Banking cheque recognition systems
* Postal code and document classification

---

##  Author

Bryan Kamanda

---


