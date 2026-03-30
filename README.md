# 🐶🐱 Dog vs Cat Image Classification using Deep Learning

## 📌 Project Overview

This project implements a **Deep Learning-based image classification system** to distinguish between **dogs and cats** using a **pretrained convolutional neural network (CNN)**. It demonstrates a complete pipeline from **data preprocessing to model prediction** using transfer learning.

---

## 🎯 Objective

* Classify images into:

  * 🐱 Cat
  * 🐶 Dog
* Leverage pretrained models to improve accuracy and reduce training time
* Build a scalable and efficient prediction system

---

## 🧠 Model Architecture

* Pretrained CNN (Transfer Learning)
* Frozen base layers for feature extraction
* Custom Dense layer for classification
* Softmax activation for final output

---

## ⚙️ Workflow

```text
Image Input
↓
Preprocessing (Resize + Normalize)
↓
Feature Extraction (Pretrained Model)
↓
Classification Layer
↓
Prediction (Cat / Dog)
```

---

## ⚙️ Steps Performed

### 🔹 Data Preprocessing

* Loaded image dataset
* Resized images to **224x224**
* Normalized pixel values (0–1 scaling)
* Converted images into NumPy arrays

---

### 🔹 Model Building

* Used pretrained model for feature extraction
* Froze base layers to retain learned features
* Added custom Dense layer for classification

---

### 🔹 Model Training

* Split dataset into training and validation sets
* Trained model using labeled data
* Optimized performance using suitable loss and optimizer

---

### 🔹 Model Evaluation

* Evaluated model using accuracy metrics
* Tested model performance on unseen data

---

### 🔹 Prediction System

* Takes image path as input
* Outputs:

  * Cat 🐱
  * Dog 🐶

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* OpenCV
* Matplotlib

---

## 📂 Project Structure

```text
dog-vs-cat-classification
│
├── dataset/
├── model/
│   └── model.h5
├── notebook/
│   └── Dog_vs_Cat_Classification.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/dog-vs-cat-classification.git
```

2. Navigate to the project folder:

```bash
cd dog-vs-cat-classification
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the notebook:

```bash
jupyter notebook
```

---

## 🧪 Run Prediction

* Provide the path of an image when prompted
* Model will classify the image as **Cat or Dog**

---

## 📊 Results

* Achieved strong classification accuracy using transfer learning
* Efficient training with reduced computation time
* Robust performance on unseen images

---

## 📌 Future Improvements

* Apply data augmentation to improve generalization
* Experiment with advanced architectures (ResNet, EfficientNet)
* Deploy model using API (FastAPI)
* Build a web interface for user interaction


