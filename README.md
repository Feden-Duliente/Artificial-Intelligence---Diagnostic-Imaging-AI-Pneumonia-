# Artificial Intelligence – Diagnostic Imaging AI (Pneumonia Detection)

## Project Overview

This project uses **Deep Learning (Convolutional Neural Networks)** to detect **Pneumonia from Chest X-ray images**.
The model classifies chest X-rays into two categories:

* NORMAL
* PNEUMONIA

This project demonstrates how **Artificial Intelligence can assist medical diagnostic imaging**.

---

## Objectives

* Build a CNN model for pneumonia detection
* Train using chest X-ray dataset
* Evaluate model performance
* Visualize predictions
* Create a reusable diagnostic AI notebook

---

## Dataset Structure

```
dataset/
│
├── train/
│   ├── NORMAL
│   └── PNEUMONIA
│
├── val/
│   ├── NORMAL
│   └── PNEUMONIA
│
└── test/
    ├── NORMAL
    └── PNEUMONIA
```

The dataset contains chest X-ray images labeled as **NORMAL** and **PNEUMONIA**. However, it is not available here in this repository because of large weight.

---

## Model Architecture

The CNN model consists of:

* Conv2D layers
* MaxPooling layers
* Flatten layer
* Dense layers
* Dropout for regularization
* Sigmoid output layer

Architecture Flow:

```
Conv2D → MaxPooling
Conv2D → MaxPooling
Conv2D → MaxPooling
Flatten
Dense
Dropout
Dense (Output)
```

---

## Requirements

Install dependencies:

```bash
pip install:
numpy
pandas
matplotlib
seaborn
tensorflow
scikit-learn
```

---

## How to Run

### 1. Clone Repository

```bash
git clone https://github.com/Feden-Duliente/Artificial-Intelligence---Diagnostic-Imaging-AI-Pneumonia-.git
```

### 2. Navigate to Project

```bash
cd Artificial-Intelligence---Diagnostic-Imaging-AI-Pneumonia-
```

### 3. Open Notebook

```
Pneumonia.ipynb
```

### 4. Run all cells

The notebook will:

* Load dataset
* Train model
* Evaluate performance
* Predict pneumonia

---

## 📊 Training Configuration

* Batch size: 32
* Epochs: 10–20
* Optimizer: Adam
* Loss: Binary Crossentropy
* Metric: Accuracy

---

## 📈 Output

The notebook generates:

* Training accuracy graph
* Validation accuracy graph
* Loss curve
* Prediction samples
* Model evaluation results

---

## Example Prediction

Input:

```
Chest X-ray image
```

Output:

```
Predicted Class: PNEUMONIA
Confidence: 97.3%

---
