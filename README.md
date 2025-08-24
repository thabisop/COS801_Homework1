# COS801_Homework1
Repo for COS801 homework 1 deliverables

# COS801 Homework 1 – CNN and Hybrid Classifiers for Weed–Crop Classification

This repository contains the notebook for **COS801 Homework 1**, which implements:
- A baseline CNN classifier
- CNN + SVM hybrid
- CNN + XGBoost hybrid

---

## 📂 Data Setup

Prepare your dataset as follows:

root folder/
└── train/
├── Class1/
│ ├── img001.png
│ ├── img002.png
│ └── ...
├── Class2/
│ ├── img010.png
│ └── ...
└── ClassN/
└── ...



- All images must be inside the `train/` folder.  
- Each subfolder represents one class.  
- The notebook automatically splits the dataset into **train, validation, and test sets** (no CSV files are needed).

---

## ⚙️ Requirements

Python 3.8+ is recommended. 
