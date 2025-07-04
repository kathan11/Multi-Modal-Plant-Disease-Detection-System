# Jamun Leaf Disease Classifier

This project contains deep learning models for classifying Jamun leaf diseases using a fusion of environmental sensor data and leaf images.

## 📁 Notebooks

- `FTT-ViT.ipynb`: Vision Transformer-based classifier trained on leaf images.
- `Fusion_Models.ipynb`: GRU + MobileNetV2 and GRU + DenseNet121 fusion models trained on combined sensor and image data.

⚠️ **Note**: The dataset is excluded due to privacy constraints.

## 📡 Data Collection

- **Sensor deployment**: DA-IICT campus (CEP Jamun field), March–December 2023.
- **Sensor frequency**: Every 30 minutes.
- **Leaf images**: Manually collected and annotated in the field.

## 🧠 Model Performance

| Model             | Test Accuracy |
| ----------------- | ------------- |
| FTT-ViT           | 95.10%        |
| GRU + MobileNetV2 | 94.64%        |
| GRU + DenseNet121 | 85.00%        |

---
