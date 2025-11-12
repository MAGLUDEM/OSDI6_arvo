# 🧠 OSDI6 arvo – TOTAL6 v2 Model (ARVO 2025)

**Author:** Dr. Manuel A. Garza León  
**Conference:** ARVO 2025  
**Institution:** Universidad de Monterrey – Centro Médico Hidalgo  
**Repository:** https://github.com/MAGLUDEM/OSDI6_arvo  

---

<p align="center">
  <a href="https://colab.research.google.com/github/MAGLUDEM/OSDI6_arvo/blob/main/OSDI6_arvo.ipynb" target="_blank">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  </a>
</p>

---

## 🔍 Overview
This repository contains the Colab notebook and frozen datasets for the **OSDI6 TOTAL6 v2** model.  
It reproduces the training, evaluation and external validation results presented at **ARVO 2025**.

**Contents:**
- `OSDI6_arvo.ipynb` — Notebook for retraining and evaluation  
- `data/` — Frozen datasets (`train.csv`, `eval.csv`, `external.csv`)  
- `models/` — Configuration and retrained model (`osdi6_model_config.json`, `osdi6_lr_balanced_colab.joblib`)

---

## 🚀 Quick Start

1. Click the badge above **“Open in Colab”** to launch the notebook.  
2. Run all cells (1–4) in order.  
3. Mount Google Drive when prompted (`/content/drive/MyDrive/OSDI6_arvo`).  
4. The notebook will automatically retrain and evaluate the model, showing AUC, AP, and performance metrics for TRAIN, EVAL, and EXTERNAL sets.

---

## 📁 Folder Structure


## 🚀 Quick start
1. Open directly in Colab:  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MAGLUDEM/OSDI6_arvo/blob/main/OSDI6_arvo.ipynb)
2. In Colab, run all cells in order (1–4).  
   Make sure you have the `data/` and `models/` folders available in Drive or in the repo.

## 📁 Folder structure


---

## 📊 Citation
Garza León M.A.  
*OSDI6 TOTAL6: Automated Ocular Surface Model.*  
Presented at **ARVO 2026**, Denver, USA.

