# 🔬 IBD-Polyp-CV

> Automated Inflammatory Bowel Disease (IBD) Severity Scoring & Polyp Detection using Computer Vision and Deep Learning.

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-2.x-orange?logo=pytorch)
![Platform](https://img.shields.io/badge/Platform-Kaggle-20BEFF?logo=kaggle)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Overview

This project builds an end-to-end deep learning pipeline that:
- 🔍 **Detects and segments polyps** from colonoscopy images
- 📊 **Scores IBD severity automatically** (Mayo Score / UCEIS)
- 🧠 **Explains predictions** using Grad-CAM visualizations
- 🚀 **Deploys as a demo** via Gradio web interface

Built from scratch as a learning project — progressing from data exploration to a fully deployed medical AI system.

---

## 🗂️ Project Structure
```
IBD-Polyp-CV/
├── notebooks/        # Kaggle notebooks (exploration, training, evaluation)
├── src/              # Reusable Python modules (dataset, model, train, utils)
├── outputs/          # Model checkpoints and results (not tracked)
├── docs/             # Notes, references, and diagrams
└── README.md
```

---

## 📊 Datasets

| Dataset | Task | Size |
|---|---|---|
| [Kvasir-SEG](https://datasets.simula.no/kvasir-seg/) | Polyp Segmentation | 1,000 images |
| [CVC-ClinicDB](https://www.kaggle.com/datasets/balraj98/cvcclinicdb) | Polyp Detection | 612 frames |
| [HyperKvasir](https://datasets.simula.no/hyper-kvasir/) | GI Classification | 110,079 images |

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Deep Learning | PyTorch, torchvision |
| Computer Vision | OpenCV, Albumentations |
| Models | U-Net, EfficientNet, YOLOv8 |
| Explainability | Grad-CAM |
| Platform | Kaggle (T4 GPU) |
| Deployment | Gradio, FastAPI |

---

## 📈 Progress Log

| Week | Task | Status |
|---|---|---|
| Week 1 | Environment setup, data exploration | ✅ Done |
| Week 2 | Data pipeline & augmentation | ✅ Done |
| Week 3 | Baseline polyp classifier | ✅ Done |
| Week 4 | U-Net polyp segmentation | ✅ Done |
| Week 5 | YOLOv8 real-time detection | ⏳ Upcoming |
| Week 6 | IBD severity scoring model | ⏳ Upcoming |
| Week 7 | Grad-CAM explainability | ✅ Done |
| Week 8 | Gradio demo + deployment | ⏳ Upcoming |

---

## 🧪 Results

| Model | Dataset | Metric | Score |
|---|---|---|---|
| EfficientNet-B0 | HyperKvasir + Kvasir-SEG | Accuracy | 99.25% |
| U-Net | Kvasir-SEG | Dice Score | 87.53% |
| Grad-CAM | Kvasir-SEG | Explainability | ✅ Visual heatmaps |

---

## 📓 Notebooks

| Notebook | Description |
|---|---|
| `01_data_exploration.ipynb` | Dataset loading, visualization, mask overlays |

---

## 👤 Author

**Pranam Acharya** — Medical AI Project, 2026

[![GitHub](https://img.shields.io/badge/GitHub-PranamAcharya10-181717?logo=github)](https://github.com/PranamAcharya10)
