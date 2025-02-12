# 🖊️ Handwritten Digits Classification Using CNN

## 📌 Project Overview
This project focuses on classifying handwritten digits (0-9) using a **Convolutional Neural Network (CNN)**. The **MNIST dataset** is used, consisting of **28x28 grayscale images** of handwritten digits. The goal is to train a deep learning model that can accurately predict the correct digit from an input image.

## 🚀 Technologies Used
- **Python**
- **TensorFlow/Keras** (for building the CNN model)
- **NumPy & Pandas** (for data handling)
- **Matplotlib** (for visualization)

## 📂 Dataset
The project uses the **MNIST dataset**, which is loaded using:
```python
from tensorflow.keras.datasets import mnist
(x_train, y_train), (x_test, y_test) = mnist.load_data()
```
## 🔧 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/handwritten-digit-classification.git
cd handwritten-digit-classification
```
