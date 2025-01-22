# MNIST Hyperparameter Tuning with Keras Tuner

This project demonstrates hyperparameter tuning using **Keras Tuner** on the **MNIST dataset** to optimize a neural network.

---

## 📋 Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Steps](#steps)
  - [1. Setting Up Keras Tuner](#1-setting-up-keras-tuner)
  - [2. Defining the Model](#2-defining-the-model)
  - [3. Configuring the Hyperparameter Search](#3-configuring-the-hyperparameter-search)
  - [4. Running the Hyperparameter Search](#4-running-the-hyperparameter-search)
  - [5. Analyzing and Using the Best Hyperparameters](#5-analyzing-and-using-the-best-hyperparameters)
- [Results](#results)
- [License](#license)

---

## 📖 Project Overview

Optimize a neural network for digit classification using the **MNIST dataset** and Keras Tuner to automate hyperparameter tuning.

---

## 🗂️ Dataset

- **Dataset**: MNIST
- **Classes**: 10 (digits 0–9)
- **Input Shape**: \(28 \times 28\)

---

## ⚙️ Steps

### 1. Setting Up Keras Tuner
- Install dependencies and preprocess the dataset.

### 2. Defining the Model
- Create a model with tunable hyperparameters (e.g., units, learning rate).

### 3. Configuring the Hyperparameter Search
- Use **RandomSearch** to optimize validation accuracy.

### 4. Running the Hyperparameter Search
- Perform a search over 5 trials with `epochs=5`.

### 5. Analyzing and Using the Best Hyperparameters
- Build and train the model with the best configuration.

---

## 📊 Results

- **Best Hyperparameters**:
  - Units: 128
  - Learning Rate: 0.001
- **Validation Accuracy**: ~96.5%

---

