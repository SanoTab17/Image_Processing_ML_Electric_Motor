<p align="center">
  <img src="assets/icon-motor.svg" width="96" alt="Project icon">
</p>

# Image Processing ML for Electric Motor Production

> Applying machine learning and image processing to **electric motor manufacturing** for defect detection, quality monitoring, and process optimization.

[![Status](https://img.shields.io/badge/status-active-brightgreen)](#)
[![Python](https://img.shields.io/badge/python-3.8+-blue)](#)
[![Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange)](#)

## 📦 Project Structure

```
Image_Processing_ML_Electric_Motor/
├── README.md
├── requirements.txt
├── notebooks/
│   └── Sanobar Workspace.ipynb
├── assets/
│   ├── icon-motor.svg
│   └── plot-XX.png
├── src/
└── data/
```

## 🚀 Quick Start

```bash
git clone https://github.com/SanoTab17/Image_Processing_ML_Electric_Motor.git
cd Image_Processing_ML_Electric_Motor

python -m venv .venv
# Windows
.venv\Scripts\activate
# Linux/Mac
source .venv/bin/activate

pip install -r requirements.txt
jupyter notebook notebooks/Sanobar Workspace.ipynb
```

## 📊 Results

![Result 1](assets/plot-01.png)

![Result 2](assets/plot-02.png)

![Result 3](assets/plot-03.png)

![Result 4](assets/plot-04.png)

![Result 5](assets/plot-05.png)

![Result 6](assets/plot-06.png)



## 🔬 Approach

- Preprocessing of image data (denoising, segmentation, feature extraction)
- ML/CV modeling (CNN, SVM, Random Forest for defect classification)
- Evaluation with accuracy, precision, recall, confusion matrix
- Visualization of results

## 🧠 Research Context

Inspired by IEEE paper: *Machine Learning in Electric Motor Production – Potentials, Challenges and Exemplary Applications*

- Potentials: predictive maintenance, quality prediction, anomaly detection
- Challenges: sensor costs, limited labeled data, need for explainable ML
- Applications: defect detection in casting/welding, winding optimization, EOL testing

## 📝 To Do

- Expand dataset with more annotated samples
- Test transfer learning with pretrained CNNs
- Add explainable AI for interpretability

## 📜 License

MIT — see LICENSE

---
_Last updated: 2025-08-24_
