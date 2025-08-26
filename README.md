# 🖋️ PCA on Handwritten Digits Dataset

This project demonstrates **Principal Component Analysis (PCA)** on the classic **Digits dataset** from `scikit-learn`.  
The goal is to reduce the dimensionality of handwritten digit images (8×8 pixels → 64 features) and visualize the data in 2D/3D space while analyzing how much variance is preserved.  

---

## 📊 Dataset
- **Source**: `sklearn.datasets.load_digits()`
- **Samples**: 1797 images
- **Features**: 64 (flattened pixel intensities from 8×8 grayscale images)
- **Labels**: Digits `0–9`

---

## 🎯 Objectives
1. Load and visualize sample digit images.
2. Standardize features for PCA.
3. Apply PCA and analyze explained variance.
4. Reduce to 2D & 3D for visualization.
5. Show how many PCs are required to preserve ~95% variance.

---

## 📂 Repository Structure
```
├── notebooks/ # Jupyter notebooks with step-by-step workflow
├── outputs/ # Plots and visualizations
  ├── results/
  ├── models/
```

---

## 📈 Visualizations
- **Sample Digits** (original images)
- **Scree Plot** – variance explained by each principal component
- **Cumulative Variance Plot** – how many PCs are needed for 90–95% coverage
- **2D Scatter Plot** – digits projected onto first 2 PCs
- **3D Scatter Plot** – digits projected onto first 3 PCs

---

## 🛠️ Tech Stack
- Python 3
- scikit-learn
- numpy
- matplotlib
