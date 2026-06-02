# star-classification-sdss

# 🌌 Star Classification Using Machine Learning (SDSS Dataset)

## 📖 Overview

This project explores how machine learning can be used to classify celestial objects such as stars, galaxies, and quasars using real telescope data from the Sloan Digital Sky Survey (SDSS).

What I like most about this project is how it connects two completely different worlds — space and computation.

A few lines of code take invisible light signals from distant objects and turn them into structured knowledge about the universe. The night sky becomes something we can actually understand.

---

## 🔭 Dataset

The dataset is based on SDSS telescope measurements.

Each object contains light intensity values in different filters:

- u (ultraviolet)
- g (green)
- r (red)
- i (infrared)
- z (deep infrared)

These values help describe how each object emits light.

---

## 🧹 Data Processing

- Removed invalid values (-9999)
- Handled missing data
- Created color features (u-g, g-r)
- Filtered clean dataset for training

---

## 🤖 Machine Learning Model

- Model: Random Forest Classifier
- Input Features: u, g, r, i, z
- Output Classes:
  - STAR
  - GALAXY
  - QUASAR

The model works like a group of decision trees voting together to decide the final classification.

---

## 📊 Visualizations

### 1. Before vs After Cleaning
Shows how raw telescope data is cleaned for machine learning.

### 2. Star Color Distribution
Visualizes how stars cluster based on brightness and color.

### 3. Star Life Stages (HR Diagram)
Shows evolution stages of stars (main sequence, giants).

### 4. Feature Importance (NASA-style)
Shows which light filters are most important for classification.

---

## 📈 Results

- Model Accuracy: ~97% (varies slightly depending on split)
- Strong performance in distinguishing star types using light patterns

---

## 🌠 Key Insight

Stars are not random points of light.

When we analyze their light scientifically, patterns emerge — revealing their temperature, brightness, and even their stage in life.

---

## 🚀 How to Run

1. Open the notebook in Google Colab or Jupyter
2. Install required libraries:
