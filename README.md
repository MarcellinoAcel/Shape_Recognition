# Shape Recognition using Deep Learning

This repository contains a complete deep learning pipeline for **geometric shape recognition** using Convolutional Neural Networks (CNN) and **transfer learning**.  
The project focuses on classifying basic geometric shapes from image data and serves as a foundational computer vision task for further robotics and AI applications.

---

## 📌 Project Overview

Shape recognition is a fundamental problem in computer vision with applications in:
- Robotics perception
- Object detection and classification
- Industrial inspection
- Educational AI systems

This project implements:
- Dataset preprocessing and splitting
- CNN-based image classification
- Transfer learning using pre-trained models
- Model training, evaluation, and visualization

All experiments are implemented in **Python using Jupyter Notebooks**.

---

## 🧠 Key Features

- ✅ Image classification using CNN
- ✅ Transfer learning for improved accuracy
- ✅ Dataset splitting and preprocessing
- ✅ Model evaluation with accuracy and loss metrics
- ✅ Clean and modular notebook workflow

---

## 🗂 Repository Structure

Shape_Recognition/
├─ geometric_shapes_dataset_split/ # Split dataset (zipped folder present)
├─ geometric_shapes_classification.ipynb # Notebook for classification modeling
├─ cnn_transfer_learning.ipynb # Notebook for transfer learning
├─ train_aas.ipynb # Auxiliary notebook
└─ README.md

:contentReference[oaicite:4]{index=4}

---

## 💡 Getting Started

These instructions will help you set up and run the project locally.

---

### 🛠 Requirements

Make sure you have the following installed:

- Python 3.8+
- Jupyter Notebook or Jupyter Lab
- TensorFlow / PyTorch (depending on model used in notebooks)
- numpy, pandas, matplotlib (common ML libraries)

You can install common dependencies using a `requirements.txt` like:

```bash
pip install -r requirements.txt
git clone https://github.com/MarcellinoAcel/Shape_Recognition.git
cd Shape_Recognition

