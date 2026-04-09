# 🎧 Speech Emotion Recognition using Deep Learning

This project builds a Speech Emotion Recognition system that classifies emotions from audio signals using machine learning.

---

## 🚀 Project Overview
- Extracted audio features using MFCC (Mel Frequency Cepstral Coefficients)
- Trained a Neural Network using PyTorch
- Predicted emotion class from speech audio

---

## 🛠 Tech Stack
- Python  
- PyTorch  
- Librosa  
- NumPy  
- Matplotlib  

---

## 📊 Model Details
- Input: Audio (.wav files)
- Feature Extraction: MFCC
- Model: Fully Connected Neural Network
- Output: Emotion class prediction

---
## 📊 Results

- Trained on ~2800+ audio samples from RAVDESS dataset  
- Observed consistent decrease in training loss during training  
- Implemented train-test split to evaluate model on unseen data  
- Model is able to predict emotion from new audio samples  

> ⚠️ Initially faced overfitting due to training on full dataset, which was resolved by introducing proper train-test evaluation.

---
## ⚙️ Pipeline

Audio (.wav)  
→ MFCC Feature Extraction  
→ Neural Network Training  
→ Evaluation (Train/Test Split)  
→ Emotion Prediction

## 💡 Use Case
This project can be used in:
- Voice assistants  
- Customer support analysis  
- Emotion-aware AI systems  

---

## 📁 Dataset
- RAVDESS Emotional Speech Dataset

---

## ▶️ How to Run
1. Open the notebook
2. Run all cells step by step
3. Upload a test audio file
4. Get predicted emotion output

