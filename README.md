# Emotion-detection-using-facial-expression-
AI-powered Facial Emotion Detection System using Deep Learning and Transfer Learning techniques with ResNet-18 for accurate real-time emotion classification across 7 human emotions.


##  Project Overview
This project focuses on developing an intelligent Facial Emotion Detection System using Deep Learning and Computer Vision techniques. The model is capable of identifying human emotions from facial images and classifying them into seven different emotion categories.

The project uses a pre-trained ResNet-18 architecture with transfer learning to achieve high accuracy and improved generalization performance.

---

## Problem Statement
Human emotions play a crucial role in communication and interaction. Traditional systems struggle to accurately identify emotions from facial expressions due to variations in lighting, pose, and facial structure.

The objective of this project is to build a robust deep learning model capable of accurately detecting emotions from facial images in real-time.

---

##  Emotion Classes
The model classifies images into the following 7 emotions:

- Angry
- Disgust
- Fear
- Happy
- Neutral
- Sad
- Surprise

---

##  Dataset
The project uses a facial emotion image dataset containing categorized facial expression images for training and testing purposes.

### Dataset Features
- RGB facial images
- Multiple emotion categories
- Preprocessed and augmented images
- Balanced train and validation split

---

##  Technologies Used

### Programming Language
- Python

### Libraries & Frameworks
- PyTorch
- Torchvision
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- OpenCV

---

##  Methodology

### 1. Data Preprocessing
- Image resizing
- Image normalization
- Data augmentation
- Train-validation split

### 2. Feature Engineering
- Automatic feature extraction using ResNet-18
- Transfer learning from ImageNet pretrained weights

### 3. Model Architecture
The project uses:
- ResNet-18 backbone
- Fully connected classifier layers
- Dropout regularization
- Softmax activation for emotion prediction

### 4. Training Process
- CrossEntropy Loss
- Adam Optimizer
- Learning Rate Scheduler
- Early stopping and regularization techniques

---

##  Model Architecture
- Pretrained ResNet-18
- Feature extraction layers
- Dropout layers (0.4 and 0.3)
- Fully connected dense layers
- Final Softmax classification layer

---

##  Evaluation Metrics
The model performance is evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

##  Results
The proposed model achieved strong performance in facial emotion recognition with improved generalization and balanced classification across all emotion classes.

### Performance Highlights
- High validation accuracy
- Reduced overfitting using dropout regularization
- Efficient feature extraction using transfer learning
- Stable precision, recall, and F1-score values

---

##  Key Features
- Deep learning-based emotion recognition
- Transfer learning with ResNet-18
- Real-time emotion classification capability
- Robust preprocessing pipeline
- Optimized training strategy

---

##  Applications
- Human Computer Interaction
- Mental Health Monitoring
- Smart Surveillance Systems
- Driver Monitoring Systems
- Online Learning Analysis
- Customer Feedback Analysis

---

##  Future Enhancements
- Real-time webcam integration
- Mobile application deployment
- Improved dataset balancing
- Attention mechanisms for better accuracy
- Deployment using Flask or Streamlit

