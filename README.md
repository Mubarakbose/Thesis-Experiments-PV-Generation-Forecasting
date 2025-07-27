# ML Model Experiments Documentation

This document provides details on the two LSTM-based forecasting models, **M1** and **M2**, used in the AI Accountability Map project. Datasets were obtained form a study by <a href="https://www.nature.com/articles/s41597-022-01696-6},
	doi = {10.1038/s41597-022-01696-6"> Chen & Xu 2022 </a>.

---

## **Model 1 (M1): Statistical Preprocessing Approach**

**Notebook:** `M1 Experiment.ipynb`

### **Overview**
Model 1 (M1) forecasts PV generation using **statistical preprocessing methods** combined with weather and power output data.

### **Contents**
- Data Loading and Preprocessing (statistics-driven)
- Exploratory Data Analysis (EDA)
- LSTM Model Architecture
- Training, Validation, and Testing
- Evaluation Metrics (MAE, MSE, RMSE, etc.)
- Forecasting Results and Visualizations

### **Key Notes**
- **Preprocessing:** Utilizes statistical feature engineering (e.g., normalization, mean/std analysis).
- **Data Split:** 70% training, 15% validation, 15% test.
- **Goal:** Accurate PV generation forecasting.

---

## **Model 2 (M2): AI-driven Preprocessing Approach**

**Notebook:** `M2 Experiment.ipynb`

### **Overview**
Model 2 (M2) forecasts PV generation using **AI-driven data preprocessing** techniques, leveraging advanced feature extraction and selection.

### **Contents**
- Data Loading and AI-based Preprocessing
- Exploratory Data Analysis (EDA)
- LSTM Model Architecture
- Training, Validation, and Testing
- Evaluation Metrics (MAE, MSE, RMSE, etc.)
- Forecasting Results and Visualizations

### **Key Notes**
- **Preprocessing:** Incorporates AI-driven feature engineering and data cleaning.
- **Data Split:** 70% training, 15% validation, 15% test.
- **Goal:** Improved performance and generalization compared to M1.

---

## **Usage Instructions**

1. Open the corresponding notebook (`M1 Experiment.ipynb` or `M2 Experiment.ipynb`) in **Jupyter Notebook** or **JupyterLab**.
2. Install dependencies:
   ```bash
   pip install tensorflow keras numpy pandas matplotlib scikit-learn
   ```
3. Run all cells sequentially to reproduce results.

---

## **Comparison of M1 vs M2**
- **M1:** Simpler statistical preprocessing, baseline model.
- **M2:** Advanced AI-driven preprocessing for potentially better accuracy and robustness.

---

> These experiments form the backbone of the PV generation forecast feature within the AI Accountability Map, enabling traceability of ML model development and evaluation.
