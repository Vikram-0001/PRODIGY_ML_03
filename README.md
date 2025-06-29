﻿# PRODIGY_ML_03
# 🐶🐱 Cat vs Dog Image Classification

This project is a machine learning-based image classification system that distinguishes between images of **cats** and **dogs**. It uses **Support Vector Machines (SVM)** for classification and **Principal Component Analysis (PCA)** for feature reduction. The model is trained and evaluated on the popular Dogs vs Cats dataset.

---

## 📂 Dataset

- **Source**: [Dogs vs Cats Dataset on Kaggle](https://www.kaggle.com/c/dogs-vs-cats/data)
- **Structure** after preparation:
train/                                                       
├── cat/                          
│ ├── cat.0.jpg                            
│ ├── cat.1.jpg                              
│ └── ...                              
├── dog/                                  
│ ├── dog.0.jpg                                   
│ ├── dog.1.jpg                              
│ └── ...                                     


---

## 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- Scikit-learn
- Matplotlib & Seaborn
- TQDM
- Joblib

---

## 🔄 Workflow

1. **Data Preparation**
 - Organize raw dataset into `cat/` and `dog/` folders.
 - Resize and convert images to grayscale.
 - Flatten image arrays into vectors.

2. **Feature Reduction**
 - Apply PCA to reduce feature dimensions and enhance performance.

3. **Model Training**
 - Use SVM (Support Vector Machine) for classification.

4. **Evaluation**
 - Display accuracy, classification report, and confusion matrix.

5. **Model Export**
 - Save the trained model using `joblib`.

---

## 📈 Output

- Accuracy score on the test dataset.
- Classification report.
- Confusion matrix heatmap.
- PCA variance plots.
- Serialized model file for deployment or reuse.

---

## 🚀 How to Run

1. **Clone the repository or download the notebook**
2. **Install required packages**:
 ```bash
 pip install numpy opencv-python matplotlib seaborn scikit-learn tqdm joblib

