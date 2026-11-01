# AI-Based Smart Waste Segregation

An AI-based waste classification system using deep learning to classify waste into four categories: **Plastic, Paper, Glass, and Organic**.

## Project Overview

Improper waste segregation creates challenges for waste management and recycling. This project aims to develop an intelligent waste classification system that uses computer vision and deep learning to identify different types of waste.

The long-term objective is to integrate the trained classification model with a hardware-based system for automated waste segregation.

## Target Categories

- Plastic
- Paper (including cardboard)
- Glass
- Organic

## Dataset

The project uses images from two datasets:

- **TrashNet:** Used for plastic, paper, and glass categories. Cardboard images are combined with paper, while the metal category is excluded.
- **AlphaTrash:** Used for the organic category.

The datasets are being prepared and organised into training, validation, and testing sets.

## Current Progress

- [x] Initial Python and NumPy practice
- [x] Matplotlib and image visualisation
- [x] Image loading and basic preprocessing
- [x] Dataset exploration and class inspection
- [x] Initial dataset preparation
- [x] TensorFlow dataset loading
- [ ] CNN model development
- [ ] Model training and evaluation
- [ ] Transfer learning using MobileNetV2
- [ ] Hardware integration and testing

## Technology Stack

- Python
- NumPy
- Matplotlib
- TensorFlow
- Google Colab

## Repository Structure

```text
AI-Waste-Segregation/
├── README.md
└── notebooks/
    └── Ai-Waste-Segregation.ipynb
```

## Project Status

**Currently in development.** The initial learning, dataset exploration, and preparation stages have been completed. Model development, training, evaluation, and hardware integration are planned next.

## Author

Developed as an academic project at IIEST Shibpur.
