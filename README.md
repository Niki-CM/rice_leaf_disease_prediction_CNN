# 🌾 Rice Leaf Disease Prediction using CNN

This project aims to classify rice leaf diseases using image-based deep learning with Convolutional Neural Networks (CNN). The model predicts one of the three diseases: **Leaf Smut**, **Brown Spot**, or **Bacterial Leaf Blight**, based on images of infected leaves.

---

## 📂 Dataset

- The dataset contains **120 JPG images**, grouped into 3 classes:
  - **Leaf Smut** (40 images)
  - **Brown Spot** (40 images)
  - **Bacterial Leaf Blight** (40 images)

> 📌 Note: Due to size limitations, dataset files are not included here. Please download them from your local source or manually unzip into the project directory.

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib, Seaborn
- PIL (for image handling)

---

## 🧠 Model Architecture

- **Convolutional Neural Network (CNN)**:
  - Conv2D + MaxPooling layers
  - Flatten
  - Dense + Dropout layers
  - Final softmax output layer (for 3 classes)

---

## 🔄 Data Preprocessing

- Images are resized and normalized.
- Data Augmentation using `ImageDataGenerator` to avoid overfitting.

---

## 📊 Model Evaluation

- Accuracy and loss are plotted during training and validation.
- Confusion matrix and classification report (to be included).
- Model tested on unseen data for generalization.

---

## 🚀 Future Enhancements

- Add web-based interface using Flask or Streamlit.
- Include model deployment with saved `.h5` or `.pkl` file.
- Expand dataset for better generalization.

---




   


