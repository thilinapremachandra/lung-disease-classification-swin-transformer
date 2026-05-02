# Lung Disease Classification using Swin Transformer

## Overview

This project implements a deep learning model for classifying lung diseases (Cancer and Pneumonia) from chest X-ray images using a Swin Transformer architecture.

## Features

- Training and validation pipeline
- Quantitative evaluation (Accuracy, F1, ROC, Confusion Matrix)
- Grad-CAM visualization for model explainability

## Dataset

Dataset is not included due to size limitations.

Download from:
[https://drive.google.com/drive/folders/1fyx5pBw3yjDkfRf2A53vOR5EtYPYQytY?usp=drive_link]

## Project Structure

```id="st1"
src/
 ├── train.py
 ├── evaluate.py
 └── gradcam.py
```

## Usage

### Train

```id="st2"
python src/train.py
```

### Evaluate

```id="st3"
python src/evaluate.py
```

### Grad-CAM

```id="st4"
python src/gradcam.py
```

## Author

Thilina Premachandra
