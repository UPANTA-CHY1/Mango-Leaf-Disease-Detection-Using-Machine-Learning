# Mango Leaf Disease Detection Using Machine Learning

# Overview
This project focuses on detecting **mango leaf diseases** using **machine learning** and **deep learning (CNNs)**.  
Traditional manual detection is time‑consuming and error‑prone. Our automated system leverages **VGG16 with transfer learning** to classify eight types of mango leaf conditions with high accuracy.

# 🎯 Objectives
- Build a CNN‑based model to classify **8 mango leaf diseases + healthy leaves**.  
- Provide farmers with a reliable diagnostic tool for **real‑time crop management**.  
- Reduce dependency on manual inspection, saving time and cost.

## 🛠️ Methodology
- **Dataset**: 4,000 balanced images across 8 categories, resized to 224×224 pixels.  
- **Model**: VGG16 with transfer learning.  
- **Training**: Adam optimizer (lr=0.0001), Sparse Categorical Cross‑Entropy loss, batch size 32, 10 epochs.  
- **Evaluation**: Precision, Recall, F1‑Score, Confusion Matrix, AUC‑ROC.  
- **Tools**: Python, TensorFlow/Keras, OpenCV, SQL for dataset handling.
  
## 📊 Results
- Achieved **99.75% accuracy** on validation data.  
- High precision and recall across most disease categories.  
- Example: Powdery Mildew classified with **99.95%–99.99% confidence**.  
- Outperformed traditional SVM baseline.

## 📚 References
- Ferentinos, K.P. *Deep learning models for plant disease detection and diagnosis*, Computers and Electronics in Agriculture, 2018.  
- Pankaj et al. *Transfer learning for anthracnose detection*, IEEE INCOGCON 2020.  
- Shorten & Khoshgoftaar. *Survey on image data augmentation for deep learning*, Journal of Big Data, 2019.  
#  Team Members
- Md. Habibur Rahman Habib   
- Faishal Uddin Himel 
- Upanta Chowdhury 
- Md. Jannatun Naim  


