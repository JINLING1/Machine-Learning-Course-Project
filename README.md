# Machine Learning Course Project

## I. Project Overview

This project focuses on an **image binary classification** task. It aims to classify facial emotions into two categories: **"Happy"** and **"Sad"**, using machine learning algorithms, particularly **Convolutional Neural Networks (CNN)**.  
🎯 **Target accuracy**: > **79%**

---

## II. Technical Solutions

- **Convolutional Neural Network (CNN)**  
  The core architecture that automatically learns spatial features in images, such as:
  - Facial expression contours  
  - Curvature of the mouth corners  
  - Shape of eyebrows  
  CNNs are highly suitable for image recognition tasks.

- **Activation Function: ReLU**  
  - Prevents vanishing gradient problems  
  - Enhances non-linear representation capabilities  
  - Improves convergence speed

- **Loss Function: Binary Crossentropy**  
  - Tailored for binary classification tasks  
  - Measures the divergence between predicted values and true labels

- **Optimizer: Adam (Adaptive Moment Estimation)**  
  - Combines momentum and adaptive learning rate  
  - Ensures faster convergence and robust optimization during training

---

## III. Dataset Source

- 📦 **Dataset**: [Dataset of faces as per emotions | Kaggle](https://www.kaggle.com)  
- 📊 **Content**:
  - **Happy**: 614 images  
  - **Sad**: 525 images  
  - **Total**: 1,139 images

---

## IV. Environment Configuration

### 4.1 Software Environment

- **Python version**: 3.10  
- **Deep Learning Framework**: TensorFlow 2.10.0  
- **Dependencies**:
  - `opencv-python`
  - `matplotlib`
  - `imghdr`

### 4.2 Setup Instructions

```bash
# Step 1: Create virtual environment
conda create -n env-name python=3.10

# Step 2: Activate virtual environment
conda activate env-name

# Step 3: Install dependencies
pip install tensorflow==2.10.0 opencv-python matplotlib imghdr
# Step 4: Launch Jupyter Notebook
```

## V. Feedback
If you have any questions or suggestions about this project, feel free to open an issue or contact me directly.
