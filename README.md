# Yoga Pose Classification Using Convolutional Neural Networks and Transfer Learning

## Project Overview

This project develops an automated yoga pose classification system using deep learning and computer vision techniques. Two image-classification approaches are implemented and compared:

* Custom Convolutional Neural Network (CNN)
* MobileNetV2 Transfer Learning Model

The objective is to investigate whether transfer learning improves classification performance compared with a conventional CNN architecture for multi-class yoga pose recognition.

---

## Dataset

**Dataset Name:** Yoga Poses Dataset

**Source:** Kaggle

**Dataset Link:** https://www.kaggle.com/datasets/niharika41298/yoga-poses-dataset

### Dataset Characteristics

| Item              | Value          |
| ----------------- | -------------- |
| Total Images      | 1,550          |
| Training Images   | 1,080          |
| Testing Images    | 470            |
| Number of Classes | 5              |
| Image Type        | RGB JPG Images |

### Yoga Pose Classes

* Downward Dog
* Goddess
* Plank
* Tree
* Warrior II

---

## Project Workflow

1. Dataset loading and validation
2. Dataset cleaning and quality checking
3. Exploratory data analysis
4. Image preprocessing and normalization
5. Data augmentation
6. Train/test preparation
7. Custom CNN development
8. MobileNetV2 transfer learning
9. Model training and optimization
10. Performance evaluation
11. Confusion matrix analysis
12. ROC curve and ROC-AUC analysis
13. Class-wise F1-score evaluation
14. Model comparison
15. Prediction-based error analysis
16. Workflow visualization and reporting

---

## Models

### Custom CNN

A baseline CNN architecture consisting of convolutional, pooling, dropout, and dense layers.

### MobileNetV2 Transfer Learning

A pretrained MobileNetV2 model fine-tuned for yoga pose classification.

---

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Classification Report
* Confusion Matrix
* ROC Curves
* ROC-AUC Scores
* Training and Validation Loss

---

## Results

### Model Performance

| Model       | Test Accuracy (%) | Test Loss |
| ----------- | ----------------- | --------- |
| Custom CNN  | 78.30             | 0.686     |
| MobileNetV2 | 84.89             | 0.426     |

### Additional Analysis

The project includes:

* Confusion Matrix Visualization
* Multi-Class ROC Curves
* ROC-AUC Performance Analysis
* Class-wise F1-Score Evaluation
* Model Comparison Charts
* Prediction Error Analysis

### Best Model

MobileNetV2 achieved the highest overall performance and demonstrated better generalization capability than the custom CNN model.

---

## Repository Structure

```text
Figures/
Results/
Models/
Notebook/
README.md
```

### Figures

* Dataset characterization dashboard
* Exploratory analysis figures
* Sample yoga pose images
* Data augmentation examples
* CNN training curves
* MobileNetV2 training curves
* Confusion matrix
* ROC curves
* Model comparison charts
* F1-score analysis
* Error analysis
* Workflow diagram

### Results

* Classification reports
* ROC-AUC performance tables
* Training logs
* Evaluation summaries
* Excel and CSV outputs

### Models

Included:

* mobilenetv2_best.keras
* mobilenetv2_final.keras

Custom CNN checkpoints exceeded GitHub upload limits and were retained in the Kaggle environment.

---

## Technologies

* Python
* TensorFlow / Keras
* MobileNetV2
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Kaggle
* GitHub

---

## Author

Maryam Moghaddas Bayat

Ph.D. in Economics
