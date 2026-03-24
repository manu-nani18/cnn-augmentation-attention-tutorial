# cnn-augmentation-attention-tutorial

# Understanding How Data Augmentation Affects Attention and Prediction Stability in CNNs

This repository contains code and materials for a machine learning tutorial investigating how different data augmentation strengths influence:

- Model convergence behaviour
- Prediction stability under perturbations
- Spatial attention patterns using Grad-CAM

## Dataset
Experiments were conducted using the CIFAR-10 dataset.
A subset of the training data was used to reduce training time,
while the full test set was retained for evaluation.

## Reproducibility Notes

Random seeds were fixed where possible to ensure consistent results.
Training was performed using transfer learning with a frozen MobileNetV2 backbone.

## Models
Transfer learning with MobileNetV2 backbone (frozen feature extractor).

Three configurations were evaluated:
- Baseline (no augmentation)
- Moderate augmentation
- Aggressive augmentation

## Repository Structure

- notebook/ → Jupyter notebooks for training and analysis
- figures/ → Visualisations used in the tutorial
- report/ → Final tutorial report (PDF)

## How to Run

1. Install dependencies:
   ! pip install -r requirements.txt

2. Open notebook:
- Augmentation_CNN

## Key Insight

Augmentation strength affects not only accuracy but also prediction stability and model attention behaviour.

## License
MIT License
