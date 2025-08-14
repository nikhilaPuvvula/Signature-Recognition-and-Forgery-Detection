# Signature-Recognition-and-Forgery-Detection


A deep learning–based offline signature verification system that combines CNN-based recognition with embedding-based forgery detection. Designed for real-world deployment, this project supports both known and new users through modular preprocessing, cosine similarity verification, and a user-friendly Colab GUI.

---

## Overview

This project tackles the challenge of verifying handwritten signatures using a hybrid approach:
- **Recognition**: Classifies signatures using a trained CNN model.
- **Verification**: Compares embeddings via cosine similarity to detect forgeries.
- **New User Support**: Verifies signatures from users not seen during training — no retraining required.

---

## Key Features

-  **CNN-Based Signer Classification**  
  Trained on genuine and forged samples to recognize known users.

-  **Embedding-Based Verification**  
  Uses cosine similarity between CNN feature vectors to detect forgeries.

-  **Modular Preprocessing Pipeline**  
  Includes border removal, binarization, scaling, centering, and rotation correction.

- **Colab-Compatible GUI**  
  Built with `ipywidgets` for interactive signature upload, mode switching, and result display.

-  **Scalable Design**  
  Easily extendable to support incremental learning and new biometric modalities.

---

##  Tech Stack

- **PyTorch** – Model training and inference  
- **NumPy, PIL** – Image preprocessing  
- **ipywidgets** – GUI interface in Colab  
- **Cosine Similarity** – Verification logic

---
