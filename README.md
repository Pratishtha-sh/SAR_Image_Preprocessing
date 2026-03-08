# SAR Image Preprocessing and Autoencoder Model

## Overview
This project implements a preprocessing pipeline for **Synthetic Aperture Radar (SAR) images**, followed by training an **autoencoder model for noise reduction**.  
The goal is to enhance the quality of SAR images by leveraging deep learning techniques.

The project uses:
- **OpenCV** for image preprocessing
- **Keras / TensorFlow** for building and training the autoencoder model

---

## Dataset
The dataset consists of SAR images categorized into multiple classes such as:

- Agriculture
- Barren Land
- Ocean
- City

Each category contains two sets of images:

- **s1** – SAR images  
- **s2** – Optical images used for comparison after processing

---

## Installation Requirements

Make sure the following dependencies are installed:

- Python 3.x
- OpenCV
- NumPy
- scikit-learn
- Keras
- TensorFlow
- Matplotlib

You can install the required libraries using:

```bash
pip install opencv-python numpy scikit-learn tensorflow keras matplotlib
