# ♻️ AI-Driven Waste Classification

## 🧠 Objective
To build an AI-based system that automatically classifies waste materials into categories such as **cardboard, glass, metal, paper, plastic, and trash** using deep learning.

---

## 📊 Dataset
The dataset was sourced from **Kaggle: Garbage Classification Dataset**.  
It contains 6 waste categories:
- 🟤 Cardboard  
- 🟡 Glass  
- ⚙️ Metal  
- 📄 Paper  
- 🧴 Plastic  
- 🗑️ Trash  

All images were **preprocessed, resized to 224×224**, and **normalized** for model compatibility.

---

## 🧩 Model Architecture
A **Convolutional Neural Network (CNN)** was developed using **TensorFlow/Keras**, leveraging the **MobileNetV2** architecture for lightweight and efficient image classification.

### ⚙️ Model Details:
- **Base Model:** MobileNetV2 (pre-trained on ImageNet)  
- **Optimizer:** Adam  
- **Loss Function:** Categorical Crossentropy  
- **Evaluation Metric:** Accuracy  

---

## 🧪 Results
| Metric | Value |
|--------|--------|
| Training Accuracy | ~73% |
| Validation Accuracy | ~70% |
| Epochs | 8 |

The model shows strong generalization performance across multiple waste categories.

---

## 🚀 How to Run
1. Open the file **`AI_Waste_Classification.ipynb`** in **Google Colab**.  
2. Mount your Google Drive and load the dataset.  
3. Run all cells sequentially to train or test the model.  

The pre-trained model file (`ai_waste_classification_model.h5`) is also available in this repository.

---

## 📁 Repository Structure
```plaintext
final_project/
│
├── AI_Waste_Classification.ipynb      # Source notebook
├── ai_waste_classification_model.h5   # Trained model
└── README.md                          # Project documentation

✨ Author

Abeer Mittal
AI Waste Classification - Final Project (Week 3)
