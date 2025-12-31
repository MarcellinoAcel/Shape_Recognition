# Shape Recognition using Deep Learning

This repository contains a complete deep learning pipeline for geometric shape recognition using Convolutional Neural Networks (CNN) and transfer learning.  
The project focuses on classifying basic geometric shapes from image data and serves as a foundational computer vision task for further robotics and AI applications.

---

## Project Overview

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

All experiments are implemented in Python using Jupyter Notebooks.

---

## Key Features

- Image classification using CNN
- Transfer learning for improved accuracy
- Dataset splitting and preprocessing
- Model evaluation with accuracy and loss metrics
- Clean and modular notebook workflow

---

## Repository Structure

Shape_Recognition/
├── geometric_shapes_dataset_split/
├── geometric_shapes_classification.ipynb
├── cnn_transfer_learning.ipynb
├── train_aas.ipynb
└── README.md

---

## Getting Started

These instructions will help you set up and run the project locally.

---

## Requirements

- Python 3.8+
- Jupyter Notebook or Jupyter Lab
- TensorFlow or PyTorch
- NumPy, Pandas, Matplotlib

---

## Installation

Clone the repository:

git clone https://github.com/MarcellinoAcel/Shape_Recognition.git  
cd Shape_Recognition

(Optional) Create virtual environment:

python -m venv venv  
source venv/bin/activate   (Linux / macOS)  
venv\Scripts\activate      (Windows)

Install dependencies:

pip install tensorflow numpy pandas matplotlib opencv-python jupyter

---

## Running the Notebooks

Start Jupyter Notebook:

jupyter notebook

Open and run:

- geometric_shapes_classification.ipynb  
  CNN-based shape classification

- cnn_transfer_learning.ipynb  
  Transfer learning implementation

- train_aas.ipynb  
  Additional training experiments

---

## Notes

- Ensure dataset paths match your local directory
- GPU is recommended for faster training
- Transfer learning usually converges faster

---

## Author

Bernard Marcellino Sitio  
AI & Robotics Enthusiast  
GitHub: https://github.com/MarcellinoAcel
