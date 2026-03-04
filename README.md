# Fake vs Real Logo Detection (MobileNet)

## Overview
This repository contains a **deep-learning logo authenticity detector** that classifies an uploaded logo as **Real** or **Fake** using a MobileNet-based CNN pipeline. The project was developed as part of an AI/ML externship and focuses on building a practical computer vision workflow for brand authentication.

---

## Project Highlights
- **Binary classification:** Real vs Fake logo detection  
- **Model:** Transfer learning using **MobileNet** with TensorFlow/Keras  
- **Pipeline:** Image preprocessing → model training → evaluation → prediction  
- **Metrics:** Includes evaluation using classification report (precision/recall/F1)

---

## Repository Contents
- `fake_logo_detection.ipynb`  
  End-to-end notebook for preprocessing, training, evaluation, and inference.

*(If your notebook file name is different, rename it here in the README.)*

---

## Tech Stack
- **Programming:** Python  
- **Deep Learning:** TensorFlow / Keras (MobileNet)  
- **Computer Vision:** OpenCV  
- **Data:** NumPy, Pandas  
- **Evaluation & Visualization:** scikit-learn, Matplotlib  

---

## Getting Started (Google Colab)

1. Open the notebook in **Google Colab** (upload it or open it from GitHub).
2. Ensure your dataset path in the notebook points to the correct location.  
   - If your dataset is stored locally, upload it to Colab.
   - If it is stored in Drive, mount Drive and update the path accordingly.
3. Run the notebook cells in order:
   - Load and preprocess dataset
   - Train MobileNet model
   - Evaluate using classification report
   - Run predictions on new images

---

## Dataset Setup
The notebook expects logo images organized into two classes (Real and Fake).

Example structure:
DATASET/
Real/
img1.png
img2.jpg
...
Fake/
img1.png
img2.jpg


Update the dataset path in the notebook to match your folder structure.

---

## Output Example
The model outputs a label for a logo image:
- **Prediction:** Real / Fake  
- **Evaluation:** classification report (precision, recall, F1-score)

---

## What I’d Do Next
- Add a simple web interface (Flask/Streamlit) for uploading and predicting logos  
- Expand dataset for more brands and more logo variations  
- Add calibration and threshold tuning to reduce false positives  
- Save and version models with a clear training + inference script structure  

---
