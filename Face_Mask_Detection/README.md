# 😷 Face Mask Detection using CNN

A deep learning-based image classification project to automatically detect whether a person is wearing a mask or not.  
This project uses a Kaggle dataset and Convolutional Neural Network (CNN) for binary classification:  
- **With Mask (1)**
- **Without Mask (0)**

---

## 📂 Dataset

Dataset Source: Kaggle  
Dataset Name: *Face Mask Dataset*  
Classes available:
- **with_mask** → 3725 images  
- **without_mask** → 3828 images  

Total images: **7553**  

The dataset is automatically downloaded and extracted using Kaggle API.

---

## 🛠️ Tech Stack

| Tool | Description |
|------|-------------|
| Python | Main programming language |
| TensorFlow | Neural network model |
| Scikit-Learn | Train/test splitting |
| Matplotlib | Visualization |
| Pillow (PIL) | Image handling |
| OpenCV | Image preview (optional) |

---

## 📦 Installation

Install Kaggle API and setup credentials:
```bash
pip install kaggle
mkdir -p ~/.kaggle
cp kaggle.json ~/.kaggle/
chmod 600 ~/.kaggle/kaggle.json
