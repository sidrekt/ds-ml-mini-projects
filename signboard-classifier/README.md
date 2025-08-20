# Synthetic Signboard Classifier (Proof of Concept)

## Overview
This project is a **proof of concept (POC)** for my larger **OCR + Signboard Classification Pipeline**.  
Here, I use a **synthetic text-only dataset of signboard content** to demonstrate the classification component before integrating it with real-world image + OCR data.

## Approach
- Created a **synthetic dataset** of signboard texts with predefined categories (e.g., advertisement, traffic, storefront, informational).  
- Preprocessed text using **TF-IDF vectorization**.  
- Trained machine learning classifiers to predict the **signboard category** from text.  
- Evaluated performance using accuracy, F1-score, and confusion matrices.  

## Why Proof of Concept?
Real-world signboards are first detected using **YOLO** and passed through an **OCR engine**. Since not all signboards contain text, this project validates the **text-only classification pipeline** in isolation before integrating into the full system.  

👉 For the complete project with **OCR + Computer Vision**, see: [Signboard OCR & Classifier](../signboard-classifier/README.md)

## Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  

## Usage
1. Clone the repository and navigate to this folder:
   ```bash
   git clone https://github.com/your-username/ds-ml-mini-projects.git
   cd ds-ml-mini-projects/synthetic-signboard-classifier
