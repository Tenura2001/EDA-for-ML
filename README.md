# EDA-for-ML
Advanced Exploratory Data Analysis (EDA)

# 🧹 Data Preprocessing Pipeline for Churn Modelling

This repository contains a structured data preprocessing pipeline designed for a churn prediction dataset. The project is organized into modular Jupyter notebooks, each handling a specific step in the preprocessing workflow.

---

## 📁 Project Structure

📁 Project Root
├── 📂 processed/                     # Directory containing preprocessed datasets
│   ├── ChurnModelling_Binned.csv          # After feature binning
│   ├── ChurnModelling_Encoded.csv         # After feature encoding
│   ├── ChurnModelling_Final.csv           # Final preprocessed dataset
│   ├── ChurnModelling_MissingHandled.csv  # After handling missing values
│   ├── ChurnModelling_OutliersHandled.csv # After handling outliers
│   └── 📂 row/
│       └── CEHHbInToW.csv                 # Raw input dataset
├── .env                                   # Environment configuration file
├── 0_handle_missing_value.ipynb          # Notebook to handle missing values
├── 1_handling_outliers.ipynb             # Notebook to handle outliers
├── 2_feature_binning.ipynb               # Notebook for feature binning
├── 3_feature_encoding.ipynb              # Notebook for feature encoding
├── 4_feature_scaling.ipynb               # Notebook for feature scaling
├── requirements.txt                      # Python dependencies
└── README.md                             # Project overview and documentation
