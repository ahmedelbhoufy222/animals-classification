# 🧠 Chest X-Ray Pneumonia Classification using CNN

## 📌 Project Description
This project builds a Convolutional Neural Network (CNN) model to classify chest X-ray images into:
- **NORMAL**: Healthy chest X-rays
- **PNEUMONIA**: X-rays showing signs of pneumonia

The model is trained and evaluated using real-world medical data from Kaggle.

---

## 📂 Dataset
- **Source**: [Chest X-Ray Pneumonia Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
- **Classes**: `NORMAL`, `PNEUMONIA`
- **Split**:
  - `Train`: Model training
  - `Val`: Validation during training
  - `Test`: Final evaluation

---

## 🧱 Model Architecture
- Input size: 180x180 RGB
- Convolutional layers + MaxPooling
- Dense layers for binary classification
- Activation: `ReLU` & `Sigmoid`
- Loss: `Binary Crossentropy`
- Optimizer: `Adam`

---

## 🧪 Results
- ✅ Accuracy: ~94%
- 📉 Loss curve and accuracy shown in training
- 🔍 Confusion Matrix & Classification Report

---

## 📊 Evaluation
- Real X-ray images are classified with high performance.
- The model can help as a baseline in medical imaging classification tasks.

---

## 📌 Next Steps
- Improve using **Transfer Learning** (e.g. ResNet, MobileNetV2)
- Perform **data augmentation**
- Add **Grad-CAM** visualization for explainability

---

## 🧑‍💻 Built With
- Python
- TensorFlow / Keras
- Matplotlib
- Google Colab
