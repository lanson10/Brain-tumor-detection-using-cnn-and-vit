Brain Tumor Detection using CNN and Vision Transformer (ViT)

This project focuses on automated brain tumor detection from MRI images using Convolutional Neural Networks (CNNs) and Vision Transformers (ViT). The goal is to classify MRI scans into tumor and non-tumor categories (or tumor types, if extended) with high accuracy.

🔍 Project Overview

Brain tumors are life-threatening if not detected early. Manual MRI analysis is time-consuming and prone to errors.
This project leverages deep learning architectures to assist radiologists and healthcare systems by providing fast and reliable predictions.

CNN captures local spatial features such as edges and textures.

ViT (Vision Transformer) captures global dependencies using self-attention, making the model robust to complex patterns.

A comparison is provided between CNN and ViT performance.

✨ Features

Preprocessing pipeline: image resizing, normalization, and augmentation.

Custom CNN model for feature extraction and classification.

ViT model fine-tuned for MRI scans.

Training and validation with accuracy, precision, recall, and F1-score metrics.

Visualization of training curves and confusion matrix.

🛠️ Tech Stack

Python

TensorFlow / Keras

PyTorch (for ViT implementation, optional)

OpenCV for preprocessing

Matplotlib & Seaborn for visualization

📂 Dataset

The project uses publicly available Brain MRI dataset (e.g., Kaggle: Brain Tumor MRI Dataset).

Dataset includes MRI images categorized into tumor and no tumor (or multiple tumor types).
