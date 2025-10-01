# Marine Drive Biodiversity Monitoring Using Deep Learning

🐟 This project focuses on monitoring marine biodiversity by detecting and classifying fish species using deep learning models.  
It uses cropped fish images and applies **transfer learning (EfficientNet)** to classify species effectively.

---

## 📊 Dataset
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
