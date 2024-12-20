# AMIA Challenge Project

This repository contains the implementation of the AMIA Challenge Project, aimed at detecting and classifying 14 abnormalities in chest X-ray images using machine learning models, DenseNet-121 and R-CNN.

## Project Overview

- **Challenge**: Automatically detect and localize abnormalities in chest X-rays to assist radiologists in diagnosis.
- **Dataset**: 15,000 annotated chest X-ray images (8,573 for training, remaining for testing).
- **Goal**: Achieve robust classification and localization of abnormalities.

## Key Components

1. **Data Processing**: Preprocessed X-ray images (1024x1024 pixels) and filtered incomplete annotations.
2. **Model Selection**: DenseNet-121 for classification and Faster R-CNN for bounding box predictions.
3. **Evaluation**: Metrics like AUC, F1 score, and IoU were used for evaluation.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/AMIA_Challenge_Project.git
   cd AMIA_Challenge_Project
