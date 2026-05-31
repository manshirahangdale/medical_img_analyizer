# 🏥 X-ray AI — Pneumonia Detection

AI-powered chest X-ray analyzer built with PyTorch and ResNet18.
Detects pneumonia from chest X-rays with **89% accuracy**.

## Demo
Upload a chest X-ray → get prediction + Grad-CAM heatmap showing
exactly where the model detected abnormalities.

## Results
| Metric | Score |
|--------|-------|
| Test Accuracy | 89% |
| Pneumonia Recall | 93% |
| Normal Precision | 87% |

## How it works
- Transfer learning with ResNet18 pretrained on ImageNet
- Fine-tuned on 5,216 chest X-rays
- Grad-CAM visualization shows model's focus area
- Interactive upload widget for real-time inference

## Dataset
[Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

## Tech Stack
- Python, PyTorch, TorchVision
- ResNet18 (Transfer Learning)
- Grad-CAM
- Jupyter / Google Colab

## View Notebook
[![nbviewer](https://img.shields.io/badge/render-nbviewer-orange)](https://nbviewer.org/github/manshirahangdale/medical_img_analyizer/blob/main/notebooks/pneumonia_classifier.ipynb)

## Motivation
Built after a friend's accident highlighted how inaccessible
specialist medical opinion can be in emergency situations.
