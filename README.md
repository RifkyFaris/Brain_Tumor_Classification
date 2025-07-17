
# Brain Tumor Classifier Full-Stack Web App 🧠💻

---

## 📌 Features

* Classifies brain tumor type from MRI scans using a deep CNN model
* Supports 4 tumor classes with high accuracy
* Responsive frontend built with **React** and **Material UI**
* Backend REST API powered by **Flask** serving TensorFlow model predictions
* Real-time data augmentation during model training for robustness
* Interactive UI showing predicted tumor class with confidence scores
* Efficient data pipeline with caching and prefetching to speed up training
* Visualization of training history and sample predictions

---

## 🔍 Dataset Details

| Feature       | Description                                 |
| ------------- | ------------------------------------------- |
| MRI Images    | Brain MRI scans from Kaggle dataset         |
| Classes       | Four tumor types (labels)                   |
| Preprocessing | Resized to 224x224, normalized pixel values |

Dataset source: [masoudnickparvar/brain-tumor-mri-dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)

---

## 🤖 Model Details

* **Architecture**: Convolutional Neural Network (CNN) with multiple Conv2D + MaxPooling layers
* **Framework**: TensorFlow and Keras
* **Input shape**: 224x224 RGB images
* **Output**: Softmax probabilities for 4 classes
* **Loss function**: Sparse Categorical Crossentropy
* **Optimizer**: Adam
* **Training epochs**: 50
* **Augmentation**: Random flips and rotations

---

## 🔗 Flask API Endpoints

| Method | Endpoint   | Description                                       |
| ------ | ---------- | ------------------------------------------------- |
| GET    | `/predict` | Accepts MRI image, returns tumor class prediction |

---

## 🖥 Frontend Overview

* Built with **React** and **Material UI** for a modern UI
* Upload MRI images and receive tumor classification results
* Displays predicted class with confidence score
* Responsive design for desktop and mobile

---


## 🧰 Tech Stack

* **Python**, **TensorFlow**, **Keras** for model training
* **FastAPI** for backend API
* **React** and **Material UI** for frontend UI
* **Kagglehub** for dataset management
* **Matplotlib** for visualization

---

## 📄 License

MIT License - feel free to use and modify!

---

