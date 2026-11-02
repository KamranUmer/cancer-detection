<div align="center">

# 🔬 Cancer Detection · YOLOv7

**Train YOLOv7 to locate cancerous regions in medical images, entirely on Google Colab.**

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"> <img src="https://img.shields.io/badge/YOLO-111F68?style=for-the-badge" alt="YOLO"> <img src="https://img.shields.io/badge/Roboflow-6706CE?style=for-the-badge&logo=roboflow&logoColor=white" alt="Roboflow"> <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">

<a href="https://colab.research.google.com/github/KamranUmer/cancer-detection/blob/main/Training_YOLOv7_on_Custom_Data.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"></a>

</div>

<p align="center"><img src="https://github.com/KamranUmer/cancer-detection/assets/86089489/15b1b6e5-06dd-4a7c-a45a-1a93c16b8a26" alt="Cancer Detection · YOLOv7 screenshot" width="85%"></p>

## 📌 Overview

An end-to-end YOLOv7 training workflow on a custom, annotated dataset of medical images: download the data from Roboflow, train on a free Colab GPU, evaluate, and reparameterise the model for faster inference.

## 🔬 Pipeline

- Dataset exported from Roboflow in YOLOv7 PyTorch format
- Custom training (20 epochs)
- Evaluation with the YOLOv7 test script
- Reparameterisation for inference

## 📊 Results

| Metric | Value |
|---|---|
| Box mAP@0.5 | 0.266 |
| Validation images | 15 |

> A short 20-epoch baseline run. More epochs and data are the obvious next step.

## 🚀 Getting Started

```bash
# Open the notebook in Google Colab (badge above), choose a GPU runtime,
# then run the cells from top to bottom.
```

## ⚠️ Disclaimer

This project is for research and learning only. It is **not** a medical device and must not be used for diagnosis or treatment decisions.

## 🙏 Acknowledgements

- [YOLOv7](https://github.com/WongKinYiu/yolov7) by WongKinYiu et al.

---

<div align="center">

Built by <a href="https://github.com/KamranUmer"><b>Kamran Umer</b></a> · ⭐ Star the repo if you find it useful

</div>
