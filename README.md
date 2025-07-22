# 🧠 Computer Vision Classification Tutorial

This repository provides a comprehensive tutorial on building an image classification model using Convolutional Neural Networks (CNNs) with the Fashion MNIST dataset. The goal is to demonstrate the complete pipeline of a computer vision task using deep learning — from loading the data to training, evaluating, and visualizing the model.

## 🎯 Objective

The project aims to classify grayscale fashion images (e.g., T-shirts, trousers, sandals) into one of 10 categories using a Convolutional Neural Network built with TensorFlow/Keras.

This tutorial helps beginners understand:

- How to load and explore image datasets  
- How to preprocess image data for neural networks  
- How to construct a CNN model using Keras  
- How to train and evaluate the model  
- How to make predictions and visualize the results  

## 📦 Dataset: Fashion MNIST

- Source: `tf.keras.datasets.fashion_mnist`  
- Contains 70,000 grayscale images in 10 categories  
  - 60,000 for training  
  - 10,000 for testing  
- Each image is 28x28 pixels in size  
- Classes include:  
  - T-shirt/top  
  - Trouser  
  - Pullover  
  - Dress  
  - Coat  
  - Sandal  
  - Shirt  
  - Sneaker  
  - Bag  
  - Ankle boot  

---

## 🗂️ File Structure & Code Explanation

This repository contains the following file:


This is the main Jupyter notebook, and it is organized into the following sections:

### 1. 📚 Importing Libraries
- `tensorflow`, `matplotlib`, `numpy`

### 2. 📥 Loading the Dataset
- Loads the Fashion MNIST dataset from `tf.keras.datasets.fashion_mnist`
- Splits into training and testing sets

### 3. 🔎 Data Exploration
- Visualizes sample images
- Shows dataset shapes and class mapping

### 4. 🧼 Data Preprocessing
- Normalizes pixel values
- Reshapes images to (28, 28, 1)

### 5. 🧠 Model Building
A CNN model with:
- Conv2D → ReLU → MaxPooling  
- Flatten → Dense → Output Softmax

### 6. 🏋️ Model Training
- Compiled with Adam & sparse categorical crossentropy  
- Trained using `.fit()`

### 7. 📈 Model Evaluation
- Evaluated on the test set with `.evaluate()`

### 8. 🔍 Predictions & Visualization
- Predicts test samples  
- Compares actual vs. predicted  
- Visual output with label match/mismatch

---

## ⚙️ Installation & Usage

### 📋 Prerequisites

👨‍💻 Author
Alaa Shorbaji
Artificial Intelligence Instructor
Machine Learning & NLP Researcher

📜 License
This project is licensed under the MIT License.

You are free to:

✅ Use and share the code for personal, academic, or commercial purposes.

✅ Modify, distribute, and build upon the code with proper credit.

You must:

❗ Provide appropriate attribution to the original author.

❗ Include this license notice in any copies or substantial portions of the project.

Disclaimer: This notebook uses open-source models and does not claim ownership of the underlying models provided by Hugging Face. All models used retain their original licenses as per their respective creators.
