# What I Learn In TensorFlow 🧠🤖

Welcome to my repository dedicated to tracking my learning journey, experiments, and progress with **TensorFlow, Deep Learning, and Neural Networks**.

This repository contains structured Jupyter Notebooks covering TensorFlow fundamentals, neural network regression, classification, computer vision, and transfer learning.

---

## 🚀 Repository Contents

### 📘 `00_fundamental_of_TensorFlow.ipynb`

* Introduction to tensors.
* Scalars, vectors, and matrices.
* Creating and manipulating tensors.
* Understanding tensor shapes and dimensions.
* TensorFlow data types.
* Mathematical operations on tensors.
* Matrix multiplication.
* Tensor indexing and slicing.

### 📗 `01_Neural_Network_Regression_with_TensorFlow.ipynb`

* Introduction to neural network regression.
* Defining input and output shapes.
* Creating TensorFlow/Keras models.
* Compiling and training neural networks.
* Evaluating models using **MAE** and **MSE**.
* Experimenting with model architecture and hyperparameters.
* Improving model performance.
* Saving and loading trained models.

### 📙 `02_Neural_Network_Classification_In_TensorFlow.ipynb`

* Introduction to neural network classification.
* Binary classification.
* Multiclass classification.
* Creating and visualizing classification datasets.
* Understanding input and output shapes.
* Building, compiling, training, and evaluating classification models.
* Experimenting with model architecture.
* Improving classification performance through tuning and experimentation.

### 📕 `03_Computer_Vision_With_TensorFlow.ipynb`

* Introduction to Computer Vision.
* Loading and preprocessing image datasets.
* Working with image tensors.
* Image data augmentation.
* Building **Convolutional Neural Networks (CNNs)**.
* Training image classification models.
* Evaluating CNN performance.
* Visualizing predictions and model outputs.
* Improving model accuracy through experimentation.
* Making predictions on custom images.

### 📓 `04_Transfer_Learning_With_Tensorflow.ipynb`

* Introduction to **Transfer Learning**.
* Understanding how pretrained models can be reused for new problems.
* Using a subset of the **Food 101** dataset with 10 food classes.
* Preparing image datasets using `ImageDataGenerator`.
* Creating training and testing data loaders.
* Implementing **TensorBoard callbacks** for experiment tracking.
* Using **TensorFlow Hub** pretrained models.
* Feature extraction using pretrained **ResNet50**.
* Feature extraction using **EfficientNetB0**.
* Building custom classification models on top of pretrained feature extractors.
* Understanding frozen pretrained layers and trainable layers.
* Training and evaluating transfer learning models.
* Visualizing training and validation **loss and accuracy curves**.
* Comparing the performance of ResNet50 and EfficientNetB0.
* Understanding different types of transfer learning:

  * As-is transfer learning
  * Feature extraction
  * Fine-tuning
* Comparing model metrics using **Pandas DataFrames**.
* Understanding TensorBoard experiment tracking and local TensorBoard usage.

---

## 🛠️ Prerequisites & Setup

To run these notebooks locally, make sure you have **Python** installed along with the required libraries.

### 1. Clone the repository

```bash
git clone https://github.com/alexandra272003/What-I-Learn-In-TensorFlow.git
cd What-I-Learn-In-TensorFlow
```

### 2. Install dependencies

```bash
pip install tensorflow tensorflow-hub jupyter numpy pandas matplotlib
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## 📚 Topics Covered

* TensorFlow Fundamentals
* Tensor Operations
* Tensor Shapes and Dimensions
* Neural Network Regression
* Neural Network Classification
* Binary Classification
* Multiclass Classification
* Model Training & Evaluation
* MAE & MSE
* Hyperparameter Tuning
* Computer Vision
* Image Preprocessing
* Data Augmentation
* Convolutional Neural Networks
* Transfer Learning
* TensorFlow Hub
* Feature Extraction
* ResNet50
* EfficientNetB0
* Model Comparison
* TensorBoard
* TensorFlow/Keras Workflows

---

## 🧠 Transfer Learning Concepts

The `04_Transfer_Learning_With_Tensorflow.ipynb` notebook explores how pretrained neural networks can be reused instead of training an entire model from scratch.

The notebook focuses mainly on **feature extraction**, where pretrained models keep their learned representations while a new classification layer is added for the target dataset.

It also introduces the three common approaches to transfer learning:

**As-is Transfer Learning**
Using an existing pretrained model without modifying it.

**Feature Extraction**
Using the learned features from a pretrained model and training a new output layer for a different classification problem.

**Fine-Tuning**
Unfreezing some or all pretrained layers and training them along with the new output layer.

---

## 📊 Model Experiments

In the transfer learning notebook, two pretrained feature extractors are experimented with:

| Model              | Approach           | Purpose                   |
| ------------------ | ------------------ | ------------------------- |
| **ResNet50**       | Feature Extraction | Food image classification |
| **EfficientNetB0** | Feature Extraction | Food image classification |

Their training and validation performance is compared using:

* Training Loss
* Validation Loss
* Training Accuracy
* Validation Accuracy
* Loss curves
* Accuracy curves

---

## ⭐ Purpose

This repository serves as my personal **TensorFlow and Deep Learning learning journal**, where I document concepts, experiments, implementations, and lessons learned while building my understanding of Machine Learning and Deep Learning.

The goal is to move from **TensorFlow fundamentals → neural networks → computer vision → transfer learning**, while learning through practical implementation and experimentation.
