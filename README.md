🐶🐱 Dog vs Cat Image Classification using Deep Learning

📌 Project Overview

This project builds a Deep Learning image classification model to distinguish between cats and dogs using a pretrained convolutional neural network (CNN).

The model leverages transfer learning to achieve high accuracy with reduced training time and computational cost.

🎯 Objective

Classify images as:

🐱 Cat

🐶 Dog

Use pretrained architecture for efficient learning

Build an end-to-end pipeline from preprocessing to prediction

🧠 Model Architecture

Pretrained CNN (Transfer Learning)

Fully Connected Dense Layer for classification

Softmax activation for output

⚙️ Steps Performed

🔹 Data Preprocessing

Loaded image dataset

Resized images to 224x224

Normalized pixel values (0–1 scaling)

Converted images into NumPy arrays

🔹 Model Building

Used pretrained model from TensorFlow

Frozen base layers to retain learned features

Added custom classification layer

🔹 Training

Split dataset into:

Training set

Validation set

Trained model on labeled images

Used categorical loss and optimizer

🔹 Evaluation

Evaluated model performance on test data

Measured accuracy and prediction performance

🔹 Prediction System

Input: Image path

Output:

“Cat” or “Dog”

🛠️ Technologies Used

Python

TensorFlow / Keras

NumPy

OpenCV

Matplotlib

📂 Project Structure

dog-vs-cat-classification
│
├── dataset/
├── model/
│   └── model.h5 / model.pkl
├── notebook/
│   └── Dog_vs_Cat_Classification.ipynb
├── README.md
└── requirements.txt

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/your-username/dog-vs-cat-classification.git

Navigate to the folder:

cd dog-vs-cat-classification

Install dependencies:

pip install -r requirements.txt

Run the notebook:

jupyter notebook

🧪 Predict on Custom Image

Provide image path when prompted

Model predicts:

Cat 🐱

Dog 🐶

📊 Results

Achieved strong classification accuracy using transfer learning

Reduced training time significantly using pretrained weights

Built a scalable image classification pipeline

📌 Future Improvements

Add data augmentation for better generalization

Use advanced architectures (ResNet, EfficientNet)

Deploy using API (FastAPI)

Build UI for real-time predictions
