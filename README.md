# Fingerprint-Based Gender Classification Using CNNs

## Overview
This project explores the application of Convolutional Neural Networks (CNNs) for gender classification from fingerprint images. By leveraging deep learning architectures, it aims to uncover patterns that distinguish male and female fingerprints, offering potential applications in forensic science and biometric security.

## Why It Matters
Traditional fingerprint analysis relies heavily on human expertise, making it subjective and time-consuming. This project investigates how AI can enhance accuracy and efficiency in gender classification, paving the way for advancements in automated biometric systems.

## How It Works
- **Deep Learning Model:** A CNN trained on fingerprint images to classify gender.
- **Dataset:** Sourced from Kaggle, preprocessed, and augmented to ensure balanced training.
- **Evaluation:** Performance assessed through accuracy metrics and classification reports.

## Get Started
1. Clone the repository:
   ```bash
   git clone https://github.com/mdiaz683/CNNFingerprints.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook cnn_gender_class.ipynb
   ```
### 🔹 Important Note: Git LFS is Required
This project uses **Git LFS** to manage large files. When cloning the repository, the dataset should download automatically **if Git LFS is installed**.

If you cloned the repo and the dataset is missing (or `images.zip` is only a few KB), install Git LFS and pull the dataset manually:

```bash
git lfs install
git lfs pull
```

📥 **The dataset is open-source, also available on Kaggle:** 
https://www.kaggle.com/datasets/ruizgara/socofing/data

For this project we are just using the folder named as "Real" in the Kaggle project.

## Paper
https://mdiaz683.github.io/assets/files/paper-fingerprints.pdf

## About the Author
Developed by **Maria Diaz Alba** | Florida International University

If you find this project useful, feel free to explore, contribute, or reach out!
