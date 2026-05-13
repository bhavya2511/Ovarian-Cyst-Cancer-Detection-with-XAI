# Ovarian Cyst Detection using Explainable AI (XAI)

## Overview

This project focuses on **ovarian cyst detection and classification** using deep learning models combined with **Explainable AI (XAI)** techniques.
The goal is to build an accurate and interpretable system for medical image analysis, helping improve trust and understanding in AI-based healthcare applications.

The project compares multiple deep learning architectures and visualizes model decisions using XAI methods such as Grad-CAM.

---

## Features

* Ovarian cyst image classification
* Comparison of multiple deep learning models
* Explainable AI visualizations
* Model performance evaluation
* Training and testing pipelines
* Accuracy, loss, confusion matrix, and classification reports

---

## Models Used

The project includes experimentation with multiple CNN-based architectures such as:

* CNN
* VGG16
* ResNet
* MobileNet
* Other transfer learning models

---

## Explainable AI (XAI)

To improve interpretability, the project uses Explainable AI techniques including:

* Grad-CAM
* Heatmap visualization
* Feature activation analysis

These methods help visualize which regions of the image influenced the model’s prediction.

---

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* OpenCV
* Scikit-learn

---

## Dataset

The dataset consists of ovarian ultrasound images categorized into different classes for training and evaluation.

> Note: Ensure the dataset is properly structured before training the models.

Example dataset structure:

```bash
dataset/
│
├── train/
│   ├── class_1/
│   ├── class_2/
│
├── validation/
│   ├── class_1/
│   ├── class_2/
│
└── test/
    ├── class_1/
    ├── class_2/
```

---

## Installation

Clone the repository:

```bash
git clone <repository-link>
cd ovarian-cyst-detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

* `ovarian-cyst-xai.ipynb`
* `ovarian_4models(1).ipynb`

---

## Results

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

XAI visualizations provide better interpretability of predictions.

---

## Project Structure

```bash
├── ovarian-cyst-xai.ipynb
├── ovarian_4models(1).ipynb
├── dataset/
├── models/
├── outputs/
├── README.md
└── requirements.txt
```

---

## Future Improvements

* Improve dataset size and diversity
* Deploy as a web application
* Add real-time prediction support
* Integrate more advanced XAI techniques

---

## Applications

* Medical image analysis
* AI-assisted diagnosis
* Healthcare decision support systems

---

## Author

Developed as a deep learning and healthcare AI project for ovarian cyst detection and explainability.
