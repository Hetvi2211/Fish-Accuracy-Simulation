# Project Ecosystem

This repository is part of a three-tier fish identification system:

- **[Deep Learning Model](https://github.com/Hetvi2211/Fish-Accuracy-Simulation)** - Core ML model for fish species identification and Similarity Search.
- **[API Backend](https://github.com/unnatii14/fish-classifier-api)** - RESTful API serving the ML model
- **[AquaVision Frontend](https://github.com/unnatii14/aquavision-flutter)** - User interface for fish identification

# Marine Drive Biodiversity Monitoring Using Deep Learning

This project focuses on monitoring marine biodiversity by detecting and classifying fish species using deep learning models.  
It uses cropped fish images and applies **transfer learning (EfficientNet)** to classify species effectively.

<img width="1675" height="807" alt="fish1" src="https://github.com/user-attachments/assets/e0d3a0e1-8c68-40ec-8dea-694d62100f8b" />

<img width="1532" height="633" alt="fish2" src="https://github.com/user-attachments/assets/9140373d-8afc-49a4-970b-3521f92307b2" />

---

## 📊 Dataset: 
- https://www.kaggle.com/datasets/markdaniellampa/fish-dataset
- **Format:** Cropped `.png` images  
- **Structure:** Images are named with species labels.  
- The notebook extracts species names from filenames and prepares them for training/validation.

---

## ⚙️ Requirements
- Python 3.x
- Jupyter Notebook
- torch, torchvision
- PIL
- seaborn, matplotlib
- pyngrok (for Colab sharing)
- google.colab (if running in Google Colab)

Install requirements (if not using Colab):
```bash
pip install torch torchvision pillow seaborn matplotlib pyngrok

### 📈 Results

Trained an EfficientNet-B0 model on cropped fish images.

Accuracy trends and performance visualizations provided.

Species-wise classification analysis included.
