# Formative 2 - Principal Component Analysis (PCA)

## Project Overview
This repository contains the **completed Colab notebook** for the Formative 2 assignment in the **Advanced Linear Algebra** module. The task focuses on implementing **Principal Component Analysis (PCA) from scratch** on a real-world Africanized dataset: the **Cost of Healthy Diet by Country (2017–2024)** dataset.  

The goal of PCA is to **reduce the dimensionality** of a dataset while retaining as much variance (information) as possible. This notebook demonstrates:
- Standardizing data using **NumPy** (no sklearn used)
- Handling missing values
- Calculating **covariance matrices**
- Performing **eigendecomposition**
- Selecting the number of **principal components dynamically**
- Projecting the dataset onto principal components
- Visualizing **before and after PCA**

---

## Dataset Information
- **Source:** Publicly available dataset on “Cost of Healthy Diet by Country (2017–2024)”  
- **Columns:** ~33 columns including numeric features (diet costs, agricultural indicators) and categorical features (Country, Region, Year)  
- **Preprocessing:**
  - Only **African countries** were selected for analysis
  - Missing values (NaNs) in numeric columns were replaced with the **column mean**
  - Categorical columns (`Country`) were excluded from PCA
- **Requirement:** >10 numeric features, missing values present, and non-numeric column included 

> **Note:** The dataset CSV is not included in this repository due to size and licensing. Download the dataset from the source and save it to your Google Drive before running the notebook.

---

## Requirements

- Python 3.x
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)

> All these packages are available by default in Google Colab.

---

## How to Run the Notebook

1. Open the notebook **`Cost_of_Healthy_Diet_PCA.ipynb`** in [Google Colab](https://colab.research.google.com/)
2. Mount your Google Drive using:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')

Author

Ogayo Andrew Ater
Advanced Linear Algebra - Formative 2 (PCA Assignment)
