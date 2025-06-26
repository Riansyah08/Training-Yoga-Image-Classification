# 🧘‍♂️ Training Yoga Image Classification — University Mini Project for Computer Vision Course
This repository contains the Training Yoga Image Classification system, developed as a Mini Project by a group of four students for the Computer Vision course.
The project aims to assist in classifying Yoga poses from images using various deep learning models. The system helps detect and classify Yoga poses based on the provided dataset to support yoga training and posture identification.

### 📦 Technologies Used
**Backend & AI Models**
- kagglehub — For dataset handling
- torch, torchvision — Deep Learning framework
- matplotlib, seaborn — Visualization
- pickle, numpy — Data handling & manipulation
- tqdm — Progress bar
- sklearn — Evaluation metrics
- cv2, PIL, io, IPython, ipywidgets — Image processing & interactive tools

### ⚙️ Project Features
- **Dataset Splitting:**
Dataset split into **80% Training** and **20% Testing**.
- **Class Imbalance Handling:**
Automatically computes **Class Weights** to handle unbalanced datasets during training.
- **Model Training & Evaluation:**
Implements multiple models for comparison:
   - ResNet
   - EfficientNet
   - VGG
   - MobileNet
   - EfficientNetB5
   - EfficientNet V2 S
- **Evaluation Metrics:**
Generates **Classification Reports** including:
   - Confusion Matrix
   - Accuracy & Loss calculation
   - Model performance comparison

### 📊 Output Example
**After training, the system provides:**
- Training and validation loss & accuracy graphs
- Final classification reports
- Confusion matrix visualizations
