SAR Image Preprocessing and Autoencoder Model
Overview:
This project implements a preprocessing pipeline for Synthetic Aperture Radar (SAR) images, followed by training an autoencoder model for noise reduction. 
The goal is to enhance the quality of SAR images by leveraging deep learning techniques. The project utilizes OpenCV for image processing and Keras for building 
and training the autoencoder.

Dataset
The dataset consists of SAR images categorized into different classes (e.g., agriculture, barren land) and divided into two sets (s1 and s2).
Each category contains optical images that can be used for comparison after processing

Installation Requirements:
Python 3.x
OpenCV
NumPy
scikit-learn
Keras
TensorFlow
Matplotlib

Usage
Prepare the Dataset: Ensure the dataset is structured as outlined above and specify the dataset_path in the code.
Load the Dataset: The CustomDataset class loads images from the specified path and prepares them for processing.
Train the Autoencoder: The autoencoder model is defined and trained on the preprocessed images. You can adjust the number of epochs and batch size as needed.
Evaluate the Model: After training, the model's performance is evaluated using Mean Squared Error (MSE).
Visualize Results: The original and reconstructed images can be visualized to assess the performance of the autoencoder.

Results
The model is trained for a specified number of epochs, with validation loss being monitored.
Final evaluation yields a Test Mean Squared Error (MSE) value, indicating the performance of the autoencoder.
