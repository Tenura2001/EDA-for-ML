# EDA-for-ML
Advanced Exploratory Data Analysis (EDA)

# 🧹 Data Preprocessing Pipeline for Churn Modelling

This repository contains a structured data preprocessing pipeline designed for a churn prediction dataset. The project is organized into modular Jupyter notebooks, each handling a specific step in the preprocessing workflow.

---

## 📁 Project Structure

```plaintext
Project Root/
├── processed/                          # Directory containing preprocessed datasets
│   ├── ChurnModelling_Binned.csv          # After feature binning
│   ├── ChurnModelling_Encoded.csv         # After feature encoding
│   ├── ChurnModelling_Final.csv           # Final preprocessed dataset
│   ├── ChurnModelling_MissingHandled.csv  # After handling missing values
│   ├── ChurnModelling_OutliersHandled.csv # After handling outliers
│   └── row/
│       └── CEHHbInToW.csv                 # Raw input dataset
├── .env                                   # Environment configuration file
├── 0_handle_missing_value.ipynb          # Notebook to handle missing values
├── 1_handling_outliers.ipynb             # Notebook to handle outliers
├── 2_feature_binning.ipynb               # Notebook for feature binning
├── 3_feature_encoding.ipynb              # Notebook for feature encoding
├── 4_feature_scaling.ipynb               # Notebook for feature scaling
├── requirements.txt                      # Python dependencies
└── README.md                             # Project overview and documentation

```
##  Notebook Overview

Each notebook performs a preprocessing task and saves an intermediate dataset to the `processed/` folder.

### ✅ 0. Handle Missing Values
- Detect and handle missing values using mean, median, or mode imputation.
- **Output:** `ChurnModelling_MissingHandled.csv`

### ✅ 1. Handle Outliers
- Identify and treat outliers using techniques such as IQR and Z-score.
- **Output:** `ChurnModelling_OutliersHandled.csv`

### ✅ 2. Feature Binning
- Convert numerical features into categorical bins (e.g., age groups).
- **Output:** `ChurnModelling_Binned.csv`

### ✅ 3. Feature Encoding
- Convert categorical variables to numeric using:
  - Label Encoding
  - One-Hot Encoding
- **Output:** `ChurnModelling_Encoded.csv`

### ✅ 4. Feature Scaling
- Standardize or normalize features using:
  - Min-Max Scaling
  - Standard Scaler
- **Output:** `ChurnModelling_Final.csv`

---

## 📊 Dataset

- **Raw Data:** `row/CEHHbInToW.csv`
- **Processed Data:** Generated and stored in the `processed/` directory after each step

---

##  Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Tenura2001/EDA-for-ML.git
cd your-repo-name
