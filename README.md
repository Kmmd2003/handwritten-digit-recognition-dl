# Handwritten Digit Recognition using Deep Learning (MNIST) 🧠✍️

This project is a deep learning-based solution to recognize handwritten **digits**, focusing especially on accurately detecting a **specific digit** in human handwriting. It is built using the popular **MNIST dataset** and leverages **Convolutional Neural Networks (CNNs)** along with **cross-validation** to achieve robust performance.

> This project was developed as part of a portfolio/resume-building effort to demonstrate skills in image classification, deep learning modeling, and model evaluation using visualization.

---

## 🚀 Features

- Digit recognition (with focus on one specific digit).
- Uses **MNIST** dataset with 70,000 labeled images.
- Built with **TensorFlow/Keras**.
- Implements **cross-validation** for better model robustness.
- Final evaluation includes **training/validation accuracy/loss plots**.
- Well-structured and commented Jupyter Notebook.

---

## 🧠 Model Overview

- **Architecture:** CNN with convolutional, pooling, and dense layers.
- **Loss Function:** Categorical Crossentropy.
- **Optimizer:** Adam.
- **Metrics:** Accuracy.
- **Cross-Validation:** K-Fold cross-validation to reduce overfitting risk.
- **Final Evaluation:** Model retrained on full dataset and evaluated with visualization.

---

## 📈 Results

- Final accuracy on test data: **~98%**
- Training convergence achieved within **X epochs**
- Detailed training/validation loss and accuracy plots included.

---

## 📂 Project Structure

```bash
📁 digi_recognition_deep_learning/
│
├── 📓 digi_recognition_deep_learning.ipynb  # Main notebook
├── 📄 README.md                             # Project documentation
└── 🗃️ (Dataset handled via Keras API)
