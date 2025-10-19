🌿 **Plant Disease Classification using TensorFlow (v1.16)**
📘 Overview
This project implements a Convolutional Neural Network (CNN) model using TensorFlow (v1.16) to classify plant leaf images into multiple disease categories.
The model is trained on an image dataset containing plant leaf samples labeled under:
Anthracnose
Die Black
Gall Midge
Healthy
The goal is to automatically detect and classify plant diseases from leaf images, helping farmers and researchers in early diagnosis and prevention.

🧠 **Model Architecture**
The model is built using TensorFlow’s Keras API,its a pretrain Tensorflow V3 model , and includes:
Convolutional layers for spatial feature extraction
MaxPooling layers for downsampling
Dropout layers for regularization
Dense layers for final classification
It uses ReLU activation for intermediate layers and Softmax activation for multi-class output.

🧩 **Dataset**
The dataset consists of images organized in folders:
├── Anthracnose
├── Die Black
├── Gall Midge
└── Healthy

Images are preprocessed using:
Rescaling (normalization)
Data augmentation (rotation, flipping, zooming)
Split into:
Training set
Validation set
Testing set
