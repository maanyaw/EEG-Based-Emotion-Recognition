# EEG-Based-Emotion-Recognition
# 🧠 EEG-Based Emotion Recognition using Deep Learning

This project focuses on recognizing emotional or perceptual states from EEG signals recorded while participants listened to music. Using the **Stanford NMED-RP EEG dataset**, we implemented a full EEG data pipeline including preprocessing, segmentation, deep learning model training, and performance evaluation.

---

## 📁 Dataset

**Source:** Stanford Naturalistic Music EEG Dataset – Rhythm Pilot (NMED-RP)  
- 5 participants  
- 128-channel dense-array EEG (EGI system)  
- Sampling Rate: 1000 Hz  
- 30-second music excerpts from 4 rhythmic categories  
- Behavioral ratings: enjoyment, rhythmic complexity, beat perception

---

## 🔧 Methodology

1. **EEG Segmentation**  
   - Trigger-based trial extraction  
   - Removal of noisy segments  
   - Selection of top 64 informative channels

2. **Preprocessing**  
   - Bandpass Filtering (1–40 Hz)  
   - Artifact removal using ICA (eye & muscle)  
   - Amplitude thresholding for noise control

3. **Deep Learning Model**  
   - EEGFormer (Transformer-based)
   











---

## 🛠️ Tech Stack

- Python 3.8+  
- PyTorch  
- NumPy 
- Scikit-learn  
- Matplotlib, Seaborn

---
