# Yoga Pose Classification Using Convolutional Neural Networks and Transfer Learning

## Project Overview

This project develops an automated yoga pose classification system using deep learning and computer vision techniques. The study compares a custom-built Convolutional Neural Network (CNN) with a MobileNetV2 transfer learning model to classify yoga poses from RGB images.

The objective is to evaluate whether transfer learning can improve classification performance compared with a conventional CNN architecture.

---

## Dataset

The dataset consists of five yoga pose categories:

* Downward Dog
* Goddess
* Plank
* Tree
* Warrior II

### Dataset Size

| Split    | Images |
| -------- | ------ |
| Training | 1080   |
| Testing  | 470    |
| Total    | 1550   |

---

## Methodology

The project workflow includes:

1. Dataset cleaning and validation
2. Exploratory data analysis
3. Image preprocessing and resizing
4. Data augmentation
5. Custom CNN model development
6. MobileNetV2 transfer learning implementation
7. Model evaluation and comparison
8. Error analysis and visualization

---

## Models

### Custom CNN

A custom convolutional neural network was developed using convolution, pooling, dropout, and fully connected layers.

### MobileNetV2 Transfer Learning

A pretrained MobileNetV2 architecture was adapted and fine-tuned for yoga pose recognition.

---

## Results

### Test Performance

| Model       | Test Accuracy (%) | Test Loss |
| ----------- | ----------------- | --------- |
| Custom CNN  | 78.30             | 0.686     |
| MobileNetV2 | 84.89             | 0.426     |

### Best Model

MobileNetV2 achieved the highest classification accuracy (84.89%) and outperformed the custom CNN model.

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

The repository includes:

* Dataset characterization dashboard
* Comprehensive exploratory profile
* Representative sample images
* Data augmentation examples
* CNN training curves
* MobileNetV2 training curves
* Confusion matrix
* Model comparison
* Class-wise F1 scores
* Prediction analysis
* Workflow diagram

### Results

Contains:

* Classification reports
* Evaluation summaries
* Training logs
* Excel and CSV outputs

### Models

Included:

* mobilenetv2_best.keras
* mobilenetv2_final.keras

Custom CNN model checkpoints exceeded GitHub web upload limits and were therefore retained in the Kaggle environment.

### Notebook

Contains the complete project notebook and implementation workflow.

---

## Technologies Used

* Python
* TensorFlow / Keras
* MobileNetV2
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## Author

Maryam Moghaddas Bayat

PhD. in Economics
