<p align="center">
  <img src="https://img.icons8.com/color/96/000000/medical-doctor.png" width="100" alt="Medical Icon"/>
</p>

<h1 align="center">Breast Cancer Prediction using Machine Learning</h1>

<p align="center">
  <a href="https://github.com/milaan9">
    <img src="https://img.shields.io/static/v1?logo=github&label=maintainer&message=milaan9&color=ff3300" alt="Maintainer"/>
  </a>
  <a href="https://hits.seeyoufarm.com">
    <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fmilaan9%2F93_Python_Data_Analytics_Projects%2Ftree%2Fmain%2F007_Breast_Cancer_Prediction_with_ML&count_bg=%231DC92C&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=views&edge_flat=false"/>
  </a>
  <img src="https://img.shields.io/badge/python-3.7%2B-blue.svg" alt="Python Version"/>
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License"/>
</p>

<p align="center">
  <img src="https://cdn.pixabay.com/photo/2017/01/31/13/14/analysis-2025785_1280.png" width="400" alt="Data Analysis"/>
</p>

---

## 🚀 Overview

This project demonstrates how to use predictive analytics and machine learning to classify breast cancer tumors as **malignant** or **benign** using real-world data. The workflow covers the entire data science pipeline, from data exploration and preprocessing to model building, evaluation, and optimization.

---

## 📑 Table of Contents

- [Project Objective](#project-objective)
- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Key Steps](#key-steps)
- [Results](#results)
- [Installation & Usage](#installation--usage)
- [Contributing](#contributing)
- [License](#license)

---

## 🎯 Project Objective

- Apply fundamental machine learning concepts to a real-world medical dataset.
- Explore, preprocess, and visualize data to extract meaningful insights.
- Build and evaluate a predictive model to classify breast cancer tumors.
- Optimize the model for improved accuracy and reliability.

---

## 🗂️ Project Structure

```
Breast_Cancer_Prediction_with_ML/
│
├── Breast_Cancer_Prediction.ipynb   # Main Jupyter notebook with code & analysis
├── data/                            # Dataset(s) used for the project
├── images/                          # Visualizations and figures
├── README.md                        # Project documentation
└── requirements.txt                 # Python dependencies
```

---

## 📊 Dataset

- **Source:** [UCI Machine Learning Repository - Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
- **Features:** 30 numeric features computed from digitized images of fine needle aspirate (FNA) of breast mass.
- **Target:** Diagnosis (Malignant = M, Benign = B)

---

## 🔑 Key Steps

### 1. Identifying the Problem & Data Acquisition
- Understand the problem statement and the nature of the dataset.
- Import and inspect the data.

### 2. Exploratory Data Analysis (EDA)
- Visualize feature distributions and relationships.
- Identify patterns and potential outliers.
- Example visualizations:
  <p align="center">
    <img src="https://seaborn.pydata.org/_images/seaborn-boxplot-1.png" width="350" alt="Boxplot Example"/>
    <img src="https://seaborn.pydata.org/_images/seaborn-pairplot-1.png" width="350" alt="Pairplot Example"/>
  </p>

### 3. Data Preprocessing
- Handle missing values and outliers.
- Feature selection and dimensionality reduction.
- Data normalization and transformation.

### 4. Model Building
- Train a Support Vector Machine (SVM) classifier.
- Evaluate using confusion matrix, ROC curve, and accuracy metrics.

### 5. Model Optimization
- Hyperparameter tuning using GridSearchCV.
- Improve model performance and generalization.

---

## 🏆 Results

- Achieved high accuracy in classifying tumors as benign or malignant.
- Visualized model performance using ROC curves and confusion matrices.
- Identified the most predictive features for breast cancer diagnosis.

---

## 💻 Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/milaan9/93_Python_Data_Analytics_Projects.git
   cd 93_Python_Data_Analytics_Projects/007_Breast_Cancer_Prediction_with_ML
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook Breast_Cancer_Prediction.ipynb
   ```

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements or suggestions.

---

<p align="center">
  <img src="https://cdn.pixabay.com/photo/2017/06/10/07/18/doctor-2388500_1280.png" width="200" alt="Doctor"/>
</p>

<p align="center">
  <b>Empowering healthcare with data-driven insights.</b>
</p>
