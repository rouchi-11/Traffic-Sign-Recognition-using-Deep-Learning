# 🚦 Traffic Sign Recognition with CNN

A deep learning project to classify road traffic signs using the **German Traffic Sign Recognition Benchmark (GTSRB)** dataset.  
Designed for autonomous vehicles to recognize speed limits, warnings, and directional signs.

---

## 🧩 Problem Statement

Autonomous cars rely on accurate perception of surroundings.  
One key component is **traffic sign recognition**.  
This project uses **Convolutional Neural Networks (CNNs)** to classify traffic signs into **43 categories** from images taken in varied real-world scenarios.

---

## 📂 Dataset

- **Source:** [GTSRB on Kaggle](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)
- **Images:** ~50,000
- **Classes:** 43
- **Train/Test CSVs:** Contain image paths and labels
- **Folders:** `Train/`, `Test/`, and `Meta/`

---

## 🛠️ Tech Stack

- Python, TensorFlow / Keras  
- OpenCV, PIL  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 🧠 Model Summary

- **Input:** 32x32 RGB images
- **Layers:**  
  - 2 × Conv2D + ReLU  
  - MaxPooling  
  - Dropout  
  - Flatten  
  - Dense layer with ReLU  
  - Output layer with Softmax (43 classes)
- **Loss Function:** Categorical Crossentropy  
- **Optimizer:** Adam  
- **Test Accuracy:** > 95%

---

## 📎 References

- [GTSRB Benchmark](https://benchmark.ini.rub.de/gtsrb_news.html)  
- [Kaggle Dataset](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)

---
