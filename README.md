# Yoga Pose Classification Using Convolutional Neural Networks and Transfer Learning

## Project Overview

This project develops a deep learning system for automated yoga pose classification using computer vision techniques. Two approaches were implemented and compared:

* Custom Convolutional Neural Network (CNN)
* MobileNetV2 Transfer Learning Model

The objective is to classify five common yoga poses from RGB images and evaluate the effectiveness of transfer learning compared with a custom-built CNN architecture.

---

## Dataset

The dataset contains five yoga pose classes:

1. Downward Dog
2. Goddess
3. Plank
4. Tree
5. Warrior II

### Dataset Size

| Split    | Images |
| -------- | -----: |
| Training |   1080 |
| Testing  |    470 |
| Total    |   1550 |

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

A custom convolutional neural network was developed using multiple convolution, pooling, dropout, and dense layers.

### MobileNetV2

A transfer learning approach using MobileNetV2 pretrained on ImageNet was implemented and fine-tuned for yoga pose classification.

---

## Results

### Test Performance

| Model       | Test Accuracy (%) | Test Loss |
| ----------- | ----------------: | --------: |
| Custom CNN  |             74.68 |     0.757 |
| MobileNetV2 |             88.72 |     0.392 |

### Best Model

MobileNetV2 achieved the highest classification accuracy and demonstrated superior generalization performance.

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

Contains:

* Dataset characterization
* Exploratory profile
* Representative sample images
* Data augmentation examples
* Training curves
* Confusion matrix
* Model comparison
* Class-wise F1 scores
* Prediction analysis

### Results

Contains:

* Classification reports
* Training logs
* Evaluation summaries
* Excel result files

### Models

Contains:

* mobilenetv2_best.keras
* mobilenetv2_final.keras

Note: Custom CNN checkpoints exceeded GitHub web upload size limits and were retained in the Kaggle environment.

### Notebook

Contains the project notebook and documentation.

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

Master's Program in Economics and Data Analytics

Frankfurt School of Finance & Management

