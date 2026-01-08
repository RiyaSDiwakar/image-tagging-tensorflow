# Image Tagging using TensorFlow

## 🔍 Overview

This project implements a basic image tagging (image classification) system using TensorFlow and Keras.
A Convolutional Neural Network (CNN) is trained to classify images into simple categories such as cat and dog.

## 🧠 Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* VS Code

## 📂 Project Structure

```
image-tagging-tensorflow/
│
├── src/
│   └── train.py        # Model training script
│
├── data/               # Dataset directory (ignored due to size)
│
├── models/             # Trained model (ignored)
│
├── .gitignore
└── README.md
```
## ⚙️ Model Details

* CNN with Conv2D, MaxPooling, Flatten, Dense layers
* Image preprocessing using `ImageDataGenerator`
* Data augmentation applied for better generalization

## 📊 Results

The model achieves reasonable accuracy on validation data for a beginner-level image classification task.

## 📌 Note

Due to GitHub file size limitations, the dataset and trained model file are not included in the repository.
They can be generated locally by running the training script.

## ▶️ How to Run
```
python src/train.py
```

## ✨ Author

Riya Diwakar
AI/ML Intern
