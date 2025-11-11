# AI-Driven Waste Classification

## 🧠 Objective
To build an AI-based system that automatically classifies waste materials into categories such as cardboard, glass, metal, paper, plastic, and trash using deep learning.

---

## 📊 Dataset
The dataset was sourced from Kaggle: **Garbage Classification Dataset**.  
It contains 6 waste categories:
- Cardboard  
- Glass  
- Metal  
- Paper  
- Plastic  
- Trash  

All images were preprocessed, resized to 224x224, and normalized.

---

## 🧩 Model Architecture
A Convolutional Neural Network (CNN) was built using **TensorFlow/Keras** based on **MobileNetV2** architecture for efficient image classification.

**Key Details:**
- Base Model: MobileNetV2 (pre-trained on ImageNet)
- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Metrics: Accuracy

---

## 🧪 Results
| Metric | Value |
|--------|--------|
| Training Accuracy | ~73% |
| Validation Accuracy | ~70% |
| Epochs | 8 |

---

## 🚀 How to Run
1. Open `AI_Waste_Classification.ipynb` in Google Colab.  
2. Mount Google Drive and load dataset.  
3. Run all cells sequentially to train or evaluate the model.  

The trained model file (`ai_waste_classification_model.h5`) is available in this repository.

---

## 📁 Repository Structure
final_project/
│
├── AI_Waste_Classification.ipynb # Source notebook
├── ai_waste_classification_model.h5 # Trained model
└── README.md # Project documentation

---

## ✨ Author
**Abeer Mittal**  
AI Waste Classification - Final Project (Week 3)
