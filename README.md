# 😴 Sleep Health & Lifestyle Analysis using K-Means Clustering and PCA

A Machine Learning project that analyzes sleep and lifestyle data using **Unsupervised Learning** techniques. This project groups individuals with similar health and lifestyle characteristics using **K-Means Clustering**, determines the optimal number of clusters using the **Elbow Method**, and visualizes high-dimensional data using **Principal Component Analysis (PCA)**.

---

## 📌 Project Overview

The goal of this project is to identify hidden patterns in people's sleep and lifestyle habits without using predefined labels.

The project performs:

- Data Cleaning
- Feature Engineering
- Data Preprocessing
- Label Encoding
- Feature Scaling
- Elbow Method
- K-Means Clustering
- PCA (Principal Component Analysis)
- Cluster Visualization
- Cluster Interpretation

---

## 📂 Dataset

**Dataset:** Sleep Health and Lifestyle Dataset

Features include:

- Gender
- Age
- Occupation
- Sleep Duration
- Quality of Sleep
- Physical Activity Level
- Stress Level
- BMI Category
- Blood Pressure
- Heart Rate
- Daily Steps
- Sleep Disorder

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

---

## 📚 Machine Learning Concepts

### Data Preprocessing

- Missing Value Handling
- Label Encoding
- Feature Scaling

### Unsupervised Learning

- K-Means Clustering
- Elbow Method

### Dimensionality Reduction

- Principal Component Analysis (PCA)

---

## 📊 Workflow

1. Import Dataset
2. Data Exploration (EDA)
3. Rename Columns
4. Split Blood Pressure into Systolic & Diastolic
5. Handle Missing Values
6. Encode Categorical Features
7. Standardize Features using StandardScaler
8. Find Optimal K using Elbow Method
9. Train K-Means Model
10. Reduce Dimensions using PCA
11. Visualize Clusters
12. Interpret Results

---

## 📈 Results

The Elbow Method suggested using **3 clusters**.

### Cluster 0

- Moderate sleep duration
- Higher stress levels
- Lower physical activity
- Lower daily steps

### Cluster 1

- Longest sleep duration
- Best sleep quality
- Lowest stress levels
- Healthy blood pressure

### Cluster 2

- Older individuals
- Higher physical activity
- Higher blood pressure
- Moderate sleep quality

These clusters reveal distinct lifestyle and health patterns among individuals.

---

## 📷 Visualizations

The project includes:

- Elbow Method Plot
- PCA Cluster Visualization

---

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Sleep-Health-Lifestyle-Analysis.git
```

Move into the project

```bash
cd Sleep-Health-Lifestyle-Analysis
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook using Jupyter Notebook or Google Colab.

---

## 📦 Requirements

```
pandas
numpy
matplotlib
scikit-learn
jupyter
```

---

## 🎯 Future Improvements

- Compare K-Means with Hierarchical Clustering
- Try DBSCAN clustering
- Build an interactive dashboard using Streamlit
- Deploy the project as a web application

---

## 👨‍💻 Author

**Nouman Saeed**

---

## ⭐ If you found this project helpful, consider giving it a star.
