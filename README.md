# 🧮 Digit Classification

This project is a **Digit Classification** system that recognizes handwritten digits (0–9) using Machine Learning.  
It is trained and tested on the **MNIST dataset** (images of size 28×28 pixels).  

---

## 📌 Features
- Preprocessing of input images  
- Training a classifier on MNIST digits  
- Model evaluation with accuracy, precision, recall, and confusion matrix  
- Prediction on custom digit images  

---

## 🚀 Tech Stack
- **Language:** Python 3  
- **Libraries:**  
  - NumPy  
  - Pandas  
  - Matplotlib / Seaborn (for visualization)  
  - scikit-learn (for ML models like KNN, SVM, Logistic Regression)  
  - TensorFlow / PyTorch (if using CNN)  

---

## 📂 Project Structure
digit-classification/
│── dataset/ # Dataset files (MNIST or custom)
│── classifiy.ipynb
│── README.md # Project documentation


# Dataset 
import kagglehub

# Download latest version
path = kagglehub.dataset_download("karnikakapoor/digits")
