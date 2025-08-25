# MNIST Digit Classifier with TensorFlow

This project implements a simple neural network using TensorFlow and Keras to classify handwritten digits from the MNIST dataset.

## 📌 Project Overview
- Dataset: [MNIST](http://yann.lecun.com/exdb/mnist/)
- Framework: TensorFlow / Keras
- Model: Fully connected feedforward neural network
  - Dense(512, ReLU)
  - Dense(10, Softmax)

## ⚙️ Steps
1. Load MNIST dataset from Keras.
2. Preprocess data (reshape + normalize).
3. Train the model with 5 epochs and batch size 128.
4. Evaluate model performance on test data.

## 🚀 Results
- Expected Accuracy: ~97% on MNIST test set.

## 📂 Files
- `mnist_classifier.ipynb` → Colab notebook with training and evaluation.

## 📌 How to Run
- Open the notebook in Google Colab or Jupyter.
- Run all cells to train and test the model.

## ✅ Future Improvements
- Add convolutional layers (CNN) for higher accuracy.
- Experiment with optimizers (Adam, SGD).
- Visualize predictions with matplotlib.

---
👩‍💻 Author: [Harsimranjeet Kaur]
