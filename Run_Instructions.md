# Running Instructions

## Project Title

Yoga Pose Classification Using Convolutional Neural Networks and Transfer Learning

---

## Repository Contents

The repository contains:

* Notebook/

  * Complete Kaggle notebook implementation

* Figures/

  * Generated project figures and visualizations

* Results/

  * Classification reports, ROC-AUC tables, and evaluation outputs

* Models/

  * Trained MobileNetV2 model files

* README.md

  * Project overview and documentation

---

## Dataset

Dataset Name:

Yoga Poses Dataset

Dataset Source:

Kaggle

Dataset Link:

https://www.kaggle.com/datasets/niharika41298/yoga-poses-dataset

---

## Recommended Environment

The project was developed and tested using:

* Kaggle Notebook
* Python 3.11+
* TensorFlow 2.x
* Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

GPU acceleration is recommended but not required.

---

## Running the Project in Kaggle

### Step 1

Open the Kaggle notebook:

### Step 2

Attach the Yoga Poses Dataset to the notebook.

### Step 3

Verify the dataset path in the notebook:

```python
DATASET_PATH = "/kaggle/input/yoga-poses-dataset/DATASET"
```

Update the path if necessary.

### Step 4

Run all notebook cells sequentially:

```text
Run All
```

The notebook performs:

* Dataset loading
* Dataset cleaning
* Exploratory data analysis
* Data augmentation
* CNN training
* MobileNetV2 training
* Performance evaluation
* ROC analysis
* Error analysis
* Figure generation

### Step 5

After execution, outputs are automatically saved to:

```text
/kaggle/working/Yoga-Pose-Recognition/
```

including:

* Figures
* Results
* Models

---

## Generated Outputs

The notebook generates:

### Figures

* Dataset characterization dashboard
* Representative sample images
* Data augmentation examples
* CNN training curves
* MobileNetV2 training curves
* Confusion matrix
* Multi-class ROC curves
* Model comparison chart
* F1-score analysis
* Error analysis
* Workflow diagram

### Results

* Classification reports
* ROC-AUC performance tables
* Evaluation summaries
* Training logs

### Models

* mobilenetv2_best.keras
* mobilenetv2_final.keras

---

## Reproducibility

The notebook uses fixed random seeds to improve reproducibility of training and evaluation results.




