# Logistic Regression – Machine Learning Hands-on

## 📌 Overview

This repository contains a beginner-friendly Python implementation of **Logistic Regression**, a supervised machine learning algorithm used for classification.

The example demonstrates how to predict whether a student will pass or fail based on study hours. It also explains the Sigmoid function and how probabilities are converted into classification results.

## 🎯 Objectives

- Understand Logistic Regression for binary classification.
- Create and train a Logistic Regression model using Scikit-learn.
- Predict student pass/fail outcomes.
- Understand the Sigmoid function.
- Calculate the probability of a student passing.
- Apply a classification threshold of 0.5.

## 🛠️ Technologies Used

- Python
- Scikit-learn
- Math module

## 📂 Project File

`logistic_regression_20_11_2026.py`

Contains the complete Python implementation of Logistic Regression and the Sigmoid function.

## 📊 Dataset

The notebook uses a simple sample dataset:

| Study Hours | Result |
|---:|---:|
| 1 | Fail (0) |
| 2 | Fail (0) |
| 3 | Fail (0) |
| 4 | Pass (1) |
| 5 | Pass (1) |
| 6 | Pass (1) |

- **Input feature (X):** Study hours
- **Target variable (y):** Pass or Fail
- `0` represents Fail
- `1` represents Pass

## 🚀 Implementation

### 1. Create and Train the Model

A Logistic Regression model is created using Scikit-learn and trained with the sample dataset.

### 2. Make Predictions

The trained model predicts the result for a student who studied 4 hours.

### 3. Sigmoid Function

The Sigmoid function converts a calculated value into a probability between 0 and 1.

\[
\sigma(z)=\frac{1}{1+e^{-z}}
\]

Where:

\[
z=b_0+b_1x
\]

In the example:

- \(b_0=-5\)
- \(b_1=1.2\)
- \(x=5\)

The calculated probability is approximately **0.7311 (73.11%)**.

### 4. Classification

A threshold of 0.5 is used:

- Probability ≥ 0.5 → Pass
- Probability < 0.5 → Fail

## 💻 How to Run

### Install the required library

```bash
pip install scikit-learn
```

### Run the Python file

```bash
python logistic_regression_20_11_2026.py
```

## 📈 Expected Output

```text
Student will Pass
Z value: 1.0
Probability: 0.7310585786300049
Student will Pass
```

## 📚 Learning Outcome

After completing this hands-on activity, learners will understand how Logistic Regression performs binary classification, how the Sigmoid function calculates probabilities, and how a threshold is used to make a final prediction.

## 👩‍💻 Hands-on Learning

**From Study Hours to Pass/Fail Prediction**

This activity introduces the fundamental concepts of classification and probability-based decision-making in machine learning.
