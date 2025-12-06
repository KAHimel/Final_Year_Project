# Final Year Project - Bangla Static Signs Detection

A deep learning–based system for recognizing **Bangla Static Sign Language gestures** using a **Vision Transformer (ViT)** model trained on a **custom dataset**.

---

## 📌 Overview

This project implements a **multi-class image classification pipeline** to recognize Bangla static sign language words from hand gesture images.  
It uses **transfer learning with Vision Transformer (ViT-B/16)** and was trained and evaluated in a **GPU-enabled Kaggle environment**.

This work was completed as a **Final Year Project (BSc in Computer Science & Engineering)**.

---

## 🚀 Features

- ✅ Custom Bangla static sign language dataset  
- ✅ Vision Transformer (ViT-B/16) with transfer learning  
- ✅ ImageFolder-based dataset handling  
- ✅ Training, evaluation, and inference pipeline  
- ✅ Single-image prediction with visualization  
- ✅ Model saving and reuse support  

---

## 🧠 Model Details

- **Architecture:** Vision Transformer (ViT-B/16)  
- **Framework:** PyTorch  
- **Pretrained Weights:** ImageNet  
- **Loss Function:** CrossEntropyLoss  
- **Optimizer:** Adam  
- **Epochs:** 25  

---

## 🗂️ Dataset

- **Type:** Custom Bangla Static Sign Language Dataset  
- **Number of Classes:** 40  
- **Split:** Train / Test  
- **Format:** Folder-based (ImageFolder)

Each folder represents one Bangla word gesture.

---

## ⚙️ Training Configuration

| Parameter       | Value     |
|----------------|-----------|
| Image Size     | 224 × 224 |
| Batch Size     | 32        |
| Learning Rate  | 3e-5      |
| Optimizer      | Adam      |
| Device         | GPU (CUDA)|

---

## 🔍 Inference

The trained model can:
- Predict Bangla sign language words from single images
- Visualize predictions with confidence
- Validate performance on unseen test images

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python) <br>
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red?logo=pytorch) <br>
![TorchVision](https://img.shields.io/badge/TorchVision-Computer%20Vision-orange) <br>
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blueviolet) <br>
![Kaggle](https://img.shields.io/badge/Kaggle-GPU%20Enabled-20BEFF?logo=kaggle) <br>


---

## 📚 Academic Context

This project was developed as part of the Final Year Project requirement for the
BSc in Computer Science & Engineering program.

The primary objective was to explore the application of
Transformer-based architectures in Bangla sign language recognition.

---

## 🔮 Future Improvements

🎥 Dynamic (video-based) sign language recognition <br>
📷 Real-time webcam-based inference <br>
📱 Mobile / desktop application deployment <br>
📈 Larger and more diverse datasets <br>
🧠 Sentence-level Bangla sign interpretation <br>

---

## 👤 Author

Kowshik Ahamed Himel(1113006). <br>
Shuborna Khandakar(1113003). <br>
BSc in Computer Science & Engineering.
