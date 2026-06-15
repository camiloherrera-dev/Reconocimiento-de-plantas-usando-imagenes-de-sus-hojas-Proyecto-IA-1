# 🌿 Automatic Plant Species Recognition from Leaf Images

A multi-model machine learning project that classifies plant species based on photographs of their leaves. Built using a **custom dataset collected on-site at UIS**, comparing supervised and unsupervised approaches across 7 different models.

> 📹 [Watch the demo video](https://www.youtube.com/watch?v=pWTUpz0_nwA) · 
> ☁️ [Open in Google Colab](https://colab.research.google.com/drive/1XLSiD-GNF1cLnzJ5Qh6WB4P_bHI7aObW?usp=sharing) · 
> 📦 [Download dataset (Drive)](https://drive.google.com/drive/folders/1m6BrNJKKu3x1ylVReK_MqgV-G8thXgvR?usp=sharing)

---

## 📌 Overview

Plant identification is a challenging computer vision problem due to variability in lighting, orientation, and species similarity. This project explores how different classical and deep learning models perform on a small, domain-specific dataset — without relying on pretrained weights or large public benchmarks.

**5 plant species** were selected and photographed directly at the Universidad Industrial de Santander (UIS) campus, making this a fully original dataset.

---

## 🧪 Models Evaluated

| Type | Model |
|---|---|
| Deep Learning | Deep Neural Network (DNN) |
| Supervised | Decision Tree |
| Supervised | Random Forest |
| Supervised | Support Vector Machine (SVM) |
| Unsupervised | K-Means Clustering |
| Unsupervised | DBSCAN |
| Unsupervised | Agglomerative Clustering |

Each model was trained and evaluated on the same dataset, enabling a direct comparison between supervised classification and unsupervised clustering approaches.

---

## 📂 Project Structure

```
├── Reconocimiento_automático_de_especies_de_plantas_...ipynb   # Main notebook
├── dataset.zip                                                  # Custom leaf image dataset (5 species, UIS)
├── Banner IA.png                                                # Project banner
└── README.md
```

---

## 🚀 Getting Started

**Option 1 — Google Colab (recommended)**  
Open the notebook directly in Colab, no setup needed:  
👉 [Open in Colab](https://colab.research.google.com/drive/1XLSiD-GNF1cLnzJ5Qh6WB4P_bHI7aObW?usp=sharing)

**Option 2 — Local**
```bash
# Install dependencies
pip install scikit-learn numpy matplotlib pandas torch jupyter

# Launch notebook
jupyter notebook
```

Then open the `.ipynb` file and run all cells.

---

## 📊 Dataset

- **Source:** Custom dataset collected at Universidad Industrial de Santander (UIS), Colombia
- **Classes:** 5 plant species identified on campus
- **Format:** Leaf images (photos), organized by species
- **Download:** [Google Drive](https://drive.google.com/drive/folders/1m6BrNJKKu3x1ylVReK_MqgV-G8thXgvR?usp=sharing)

---

## 👥 Authors

- **Camilo Andrés Herrera Celis** — [GitHub](https://github.com/camiloherrera-dev)
- **Alejandro Moreno Cortes**
- **Marlon David Osorio Monroy**

Universidad Industrial de Santander · AI Course Project
