# ✍️ Handwritten Digit Recognition — AI (Nottingham ML Internship)

> Deep Learning model that recognizes handwritten digits with **94% test accuracy**, featuring a self-improving loop via Gradio web interface. Developed during ML Internship at **University of Nottingham** (July–August 2024).

[![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-CNN-red?logo=pytorch)](https://pytorch.org)
[![OpenCV](https://img.shields.io/badge/OpenCV-Image%20Processing-green?logo=opencv)](https://opencv.org)

---

## 📊 Model Performance

| Metric | Value |
|---|---|
| Test Accuracy | **94%** |
| Architecture | CNN (Convolutional Neural Network) |
| Framework | PyTorch |
| Preprocessing | OpenCV normalization & augmentation |

---

## 🧠 Features

- **Digit Recognition:** Predicts handwritten digits (0–9) from user input
- **Self-Improving Loop:** Users can correct mispredictions → corrections are added to the dataset → model retrains with one button click
- **Web Interface:** Gradio-based UI for drawing digits and reviewing predictions

---

## 🛠️ Tech Stack

```
Deep Learning    →  PyTorch · CNN Architecture
Image Processing →  OpenCV · NumPy · Pillow
Web Interface    →  Gradio
Evaluation       →  Precision · Recall · F1-Score · Accuracy
```

---

## ⚙️ Installation

```bash
git clone https://github.com/ihsanagir/elyazisi_rakam_ai.git
cd elyazisi_rakam_ai
pip install -r requirements.txt
```

**Run the app:**
```bash
python app.py
```

---

## 🖥️ Screenshot

![App Screenshot](https://github.com/user-attachments/assets/c56eb76b-ef34-4200-8ddf-25f95d4d03c7)

---

## 🔬 How It Works

1. **Preprocessing:** Input images are normalized and augmented using OpenCV
2. **Inference:** CNN model predicts the digit class
3. **Correction:** User marks incorrect predictions via the Gradio interface
4. **Retraining:** Corrected samples are added to the training set; model retrains in one click
5. **Improvement:** Each retraining cycle improves model performance over time

---

## 🌐 Context

This project was developed during an international **Machine Learning Internship at the University of Nottingham** as part of research into 3D manufacturing technology and intelligent recognition systems.

---

## 📄 License

MIT License
