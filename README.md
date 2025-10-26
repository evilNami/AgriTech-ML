# 🛰️ AgTech ML: Hyperspectral Agriculture Classification

  
🚀 Overview

**AgTech ML** is a Machine Learning project focused on applying remote sensing and advanced algorithms to precision agriculture. The core objective is to accurately **classify different crop types** and assess **crop health** using **hyperspectral satellite imagery**. This solution provides high-resolution, predictive insights that assist farmers and agricultural strategists in optimizing resource management and improving yields.

The project utilizes a data pipeline that includes image processing, feature extraction, and the comparative evaluation of multiple machine learning classifiers.

🎯 Project Objectives

## 📊 Dataset

The analysis relies on two publicly available, high-quality agricultural image datasets from Kaggle, crucial for the classification task:

| Dataset Name | Source | Purpose in Project |
| :--- | :--- | :--- |
| **PlantDoc Dataset** | [Kaggle Link](https://www.kaggle.com/datasets/nirmalsankalana/plantdoc-dataset) | Used for **plant disease detection** and fine-tuning models on a diverse, real-world image collection. |
| **PlantVillage Dataset** | [Kaggle Link](https://www.kaggle.com/datasets/mohitsingh1804/plantvillage) | Used for **initial crop health classification** and providing a foundational set of labeled images for model training. |

✅ **Feature Engineering:** Process raw spectral bands to extract meaningful features relevant to crop type and health.
✅ **Comparative Modeling:** Implement and evaluate performance across classical and deep learning models, specifically **Random Forest (RF)** and **Convolutional Neural Networks (CNN)**.
✅ **Classification:** Achieve high-accuracy classification of various **crop types** using the selected optimal model.
✅ **Geospatial Insights:** Demonstrate the ability to visualize predicted classifications as geospatial maps for actionable intelligence.

🛠️ Tools and Technologies

**Programming Language & Environment:**
* **Python** 🐍: Core programming language for data handling, modeling, and analysis.
* **Google Colab:** Used for interactive development, experimentation, and leveraging GPU acceleration.

**Machine Learning & Processing Libraries:**
* **Scikit-learn (Sklearn):** Used for implementing and evaluating the **Random Forest** classifier.
* **TensorFlow/Keras or PyTorch:** Used for building, training, and evaluating the deep learning **CNN** model.
* **Pandas, NumPy:** Fundamental libraries for data manipulation and numerical operations.

**Classification Algorithms:**
* **Random Forest (RF)** 🌳
* **Convolutional Neural Networks (CNN)** 🧠

📂 Repository Structure

.
├── data/                  # Raw and processed hyperspectral image tiles
├── notebooks/             # Primary executable scripts
│   └── Agriculture_Classification.ipynb # The main Google Colab notebook
├── models/                # Saved trained CNN and RF models
├── documentation/         # Project reports
│   └── Q1079478_Agriculture_Classification.pdf # The comprehensive project report
├── visuals/               # Generated classification maps and performance charts
├── src/                   # Utility Python scripts (e.g., data loading, processing)
├── README.md              # Project overview and guidelines (You are here!)
└── requirements.txt       # Python dependencies (TensorFlow, Scikit-learn, etc.)
