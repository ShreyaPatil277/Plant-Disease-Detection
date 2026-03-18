# 🌿 Plant Disease Detection using Deep Learning

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Accuracy](https://img.shields.io/badge/Accuracy-96--99%25-brightgreen)


A deep learning project that detects plant diseases from leaf images
using CNN and MobileNetV2 Transfer Learning.

## 📊 Dataset
- **Source:** [New Plant Diseases Dataset](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)
- **Images:** 87,900
- **Classes:** 38 (14 plants × healthy/diseased)
- **Split:** Pre-split train / val / test

## 🧠 Models
| Model | Accuracy | Training Time |
|---|---|---|
| Custom CNN | ~88–92% | ~30 min |
| MobileNetV2 TL | ~96–99% | ~20 min |

## 🚀 How to Run

### On Google Colab (Recommended)
1. Open `notebooks/Plant_Disease_Detection_v2.ipynb` in Colab
2. Set Runtime → GPU (T4)
3. Run All Cells

### On Local Machine
```bash
git clone https://github.com/YOUR_USERNAME/plant-disease-detection.git
cd plant-disease-detection
pip install -r requirements.txt
python src/train.py
```

## 📂 Project Structure
```
plant-disease-detection/
├── notebooks/   ← Jupyter notebooks
├── src/         ← Python source files
├── outputs/     ← Plots and visualizations
└── models/      ← Saved model files (not tracked by git)
```

## 🌿 Supported Plants
Apple, Blueberry, Cherry, Corn, Grape, Orange, Peach,
Pepper, Potato, Raspberry, Soybean, Squash, Strawberry, Tomato


## 📚 References
- Hughes & Salathé (2015) — PlantVillage Dataset
- Howard et al. (2017) — MobileNets
