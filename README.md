# image-classification-cifar10
A Convolutional Neural Network (CNN) built using TensorFlow/Keras to classify images from the CIFAR-10 dataset into 10 categories like airplanes, cars, cats, and more. Includes model training, evaluation, and prediction.

# 🧠 CNN Image Classifier - CIFAR-10 Dataset

This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify images from the CIFAR-10 dataset. The model is trained to recognize and categorize images into one of ten classes such as airplanes, cats, trucks, and more.

---

## 📂 Dataset - CIFAR-10

- **Images**: 60,000 color images of size 32x32 pixels
- **Classes**: 10 (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck)
- **Split**: 50,000 training and 10,000 testing images
- **Source**: Available directly via `tensorflow.keras.datasets`

---

## 🏗️ Model Architecture

The CNN architecture used in this project includes:

- **Conv2D Layers**: Learn spatial hierarchies of features
- **MaxPooling2D**: Downsamples the feature maps to reduce complexity
- **Flatten**: Converts 2D features to 1D before passing to Dense layers
- **Dense Layers**: Fully connected layers for classification
- **Softmax Activation**: Outputs probability distribution over 10 classes

---

## 📦 Libraries Used

- `tensorflow` / `keras`
- `numpy`
- `matplotlib` (for visualizations)

---

## 🚀 How to Run

1. **Clone the Repository**  
```bash
git clone https://github.com/yourusername/cnn-cifar10-classifier.git
cd cnn-cifar10-classifier
