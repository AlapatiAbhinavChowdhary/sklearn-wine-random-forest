<div align="center">

# 🍷 Wine Quality Classification ML
### End-to-End Machine Learning Pipeline

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

<p align="center">
  <i>Classifying wine cultivars using Chemical Analysis & Random Forest Algorithms</i>
</p>

</div>

---

## 🎨 Project Overview
This project demonstrates a complete **Machine Learning Lifecycle** using the famous UCI Wine Dataset. It goes beyond simple modeling to include data preprocessing, hyperparameter tuning, pipeline creation, and model serialization for deployment.

> [!TIP]
> **Goal:** Predict the wine class (0, 1, or 2) based on 13 chemical features like Alcohol, Malic Acid, and Flavanoids.

---

## 🚀 The Pipeline

I built a robust pipeline that handles everything from raw data to a saved model file.

```mermaid
graph LR;
    A[🍷 Raw Data] -->|Load & Inspect| B(🧹 Preprocessing);
    B -->|StandardScaler| C{🤖 Model Training};
    C -->|Random Forest| D[📈 Evaluation];
    D -->|GridSearch Tuning| E[⚡ Optimization];
    E -->|Pickle/Joblib| F[💾 Saved Model.pkl];
    style A fill:#ff9999,stroke:#333,stroke-width:2px
    style B fill:#99ccff,stroke:#333,stroke-width:2px
    style C fill:#99ff99,stroke:#333,stroke-width:2px
    style F fill:#ffff99,stroke:#333,stroke-width:2px
