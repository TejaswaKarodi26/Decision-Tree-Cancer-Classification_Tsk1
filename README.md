# 🧠 Decision Tree Classifier – Cancer Diagnosis

This project demonstrates a simple and effective implementation of a **Decision Tree Classifier** using **scikit-learn** to predict whether a tumor is **malignant** or **benign**.

---

## 📂 Repository Contents

- `Cancer_Classification_DecisionTree.ipynb` – The main notebook with all steps from data loading to model evaluation
- `Cancer_Data.csv` – The dataset used (based on Kaggle’s Breast Cancer Wisconsin Diagnostic dataset)
- `Confusion_Matrix.png` – Tabular confusion matrix output
- `decision_tree_visual.png` – Exported image of the trained decision tree

---

## 📊 Dataset Information

- **Source**: Based on [Kaggle – Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Features**: 30 numerical measurements (e.g., radius, texture, perimeter, etc.)
- **Target Variable**: `diagnosis`
  - `M` = Malignant → 1
  - `B` = Benign → 0
- **Total Samples**: 569

---

## ✅ What This Project Does

1. Loads and processes a real-world cancer dataset
2. Converts categorical labels into numerical format
3. Splits the data into training and testing sets
4. Trains a Decision Tree Classifier using `scikit-learn`
5. Evaluates model performance using accuracy and confusion matrix
6. Saves and displays a visualization of the trained tree

---

## ▶️ How to Run

1. Open `Cancer_Classification_DecisionTree.ipynb` in Jupyter Notebook or Google Colab
2. Ensure all files (including `Cancer_Data.csv`) are in the same directory or uploaded
3. Run all cells step-by-step
4. Check outputs and open:
   - `confusion_matrix.csv` for the model's prediction results
   - `decision_tree_visual.png` for the graphical representation of the trained model

---

## 🛠️ Requirements

- Python 3.x
- Libraries used:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`

No external dependencies beyond standard Python ML stack.

---

## 📌 Tags

`Machine Learning` `Decision Tree` `scikit-learn` `Cancer Classification` `Kaggle Dataset` `Jupyter Notebook`

