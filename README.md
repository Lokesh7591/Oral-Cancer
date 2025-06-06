# Oral-Cancer classification using Deep Learning (VGG19)
Oral Cancer classification using Deep Learning (VGG19) This project uses deep learning to classify oral cavity images into cancerous and non-cancerous categories. The model leverages VGG19 through transfer learning and is trained on a labeled dataset of oral images sourced from Mendeley Data.


Key Features:

Used VGG19 pretrained on ImageNet with a custom classification head

Applied image preprocessing and augmentation.

Achieved 87% accuracy on binary classification.

Evaluated using accuracy, confusion matrix, precision, recall, and F1-score.


Technologies Used:

Python, TensorFlow/Keras

VGG19 CNN architecture

NumPy, Matplotlib

Google Colab / Jupyter Notebook


Dataset:

Source: Oral Cancer Images Dataset – Mendeley Data

Contains two classes: Cancerous and Non-Cancerous oral images

All images resized to 224x224 and normalized for input into VGG19


Results:

Test Accuracy: 87%.

Strong baseline performance for medical image classification.

Can be extended with interpretability tools.

